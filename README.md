NAFLD Diagnosis using Machine Learning

This project leverages various machine learning models to predict Non-Alcoholic Fatty Liver Disease (NAFLD) based on medical diagnostic data. The workflow involves data preprocessing, feature engineering, hyperparameter tuning, and model evaluation to identify the most effective classifier.

Features and Functionality

- Data Preprocessing:
  - Handles missing values using mean imputation.
  - Encodes categorical variables (e.g., gender).
  - Scales features using Min-Max Scaling.
  - Applies feature weighting based on domain knowledge.
  - Removes redundant features for specific models.

- Model Training:
  - Implements multiple classifiers, including:
    - XGBoost
    - Support Vector Machine
    - Decision Tree
    - Random Forest
    - k-Nearest Neighbors
    - Stochastic Gradient Descent
  - Fine-tunes models using Grid Search and Random Search techniques.

- Evaluation:
  - Generates classification reports and confusion matrices for model performance assessment.
  - Visualizes confusion matrices using Seaborn heatmaps.

Dataset

The dataset includes medical diagnostic features such as:

- direct_bilirubin
- tot_bilirubin
- tot_proteins
- albumin
- ag_ratio
- sgpt
- sgot
- alkphos

The target variable, is_patient, indicates NAFLD diagnosis.

Dependencies

- Python 3.7+
- NumPy
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- XGBoost

Results

Models are evaluated based on accuracy, precision, recall, and F1 score. Hyperparameter tuning is performed using Grid Search and Random Search for optimal results.
