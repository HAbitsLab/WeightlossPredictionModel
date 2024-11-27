# WeightlossPredictionModel

# Random Forest Model for Weight Loss Prediction

This project implements a **Random Forest classifier** to predict weight loss outcomes based on demographic, psychological, and physiological features. The workflow includes data preprocessing, model tuning using Bayesian optimization, and explainability analysis with **SHAP**.

## Features
- **Data Preprocessing**: Splits data into train, validation, and test sets with stratification based on gender and ethnicity.
- **Model Tuning**: Utilizes `BayesSearchCV` to optimize hyperparameters of the Random Forest classifier.
- **Model Evaluation**: Calculates metrics such as F1 score, sensitivity, specificity, ROC AUC, and precision-recall.
- **Explainability**: Uses **SHAP** for feature importance and interpretability of predictions.
- **Threshold Optimization**: Determines the best decision threshold for the classifier to maximize F1 score.

## Dependencies
Key Python packages used:
- `pandas`
- `numpy`
- `scipy`
- `scikit-learn`
- `shap`
- `matplotlib`
- `skopt`

## Usage
1. Preprocess the dataset (`SMART_Trial_Weight_Features.csv`) for model training.
2. Tune the Random Forest hyperparameters using Bayesian optimization.
3. Evaluate the model on test data and visualize results.
4. Use **SHAP** to analyze feature contributions to predictions.

## Output
- Classification metrics (e.g., F1 scores, ROC AUC).
- **SHAP** summary plots and force plots.
- Optimized decision threshold for binary classification.
