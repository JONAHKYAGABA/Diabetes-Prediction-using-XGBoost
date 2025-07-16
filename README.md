# 🧪 Diabetes Prediction using XGBoost

This project builds a machine learning pipeline for predicting diabetes using structured patient data. It leverages the powerful XGBoost classifier to train on health metrics and evaluate model performance using multiple statistical metrics and visualizations.

## ✅ Features

- Loads cleaned diabetes data from CSV
- Splits data into training and test sets
- Trains an XGBoost classifier for binary classification (diabetic vs non-diabetic)
- Evaluates model with:
  - Accuracy, Precision, Recall, F1 Score
  - Confusion Matrix
  - ROC Curve and AUC Score
- Saves trained model to disk for future inference

## 📊 Dataset

The dataset is expected to be a CSV file with structured features representing health-related parameters. The target variable is binary, indicating the presence (1) or absence (0) of diabetes.

Expected CSV location:
```bash
./diabetes_cleaned.csv
