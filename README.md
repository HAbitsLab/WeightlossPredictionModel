# WeightlossPredictionModel

This project implements a Random Forest classifier to predict weight loss outcomes based on demographic, behavioral, and clinical features. The workflow includes data preprocessing, model tuning using Bayesian optimization, and explainability analysis with SHAP.

Features
Data Preprocessing: Splits data into train, validation, and test sets with stratification based on gender and ethnicity.
Model Tuning: Utilizes BayesSearchCV to optimize hyperparameters of the Random Forest classifier.
Model Evaluation: Calculates metrics such as F1 score, sensitivity, specificity, ROC AUC, and precision-recall.
Explainability: Uses SHAP for feature importance and interpretability of predictions.
Threshold Optimization: Determines the best decision threshold for the classifier to maximize F1 score.
Dependencies
Key Python packages used:

pandas
numpy
scipy
scikit-learn
shap
matplotlib
Usage
Preprocess the dataset (SMART_Trial_Weight_Features.csv) for model training.
Tune the Random Forest hyperparameters using Bayesian optimization.
Evaluate the model on test data and visualize results.
Use SHAP to analyze feature contributions to predictions.
Output
Classification metrics (e.g., F1 scores, ROC AUC).
SHAP summary plots and force plots.
Optimized decision threshold for binary classification.
Let me know if you need further customization!
