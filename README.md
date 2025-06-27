# Deposit Prediction using Cloud-Ready ML Model

This machine learning project predicts whether a customer will make a deposit in a bank marketing campaign based on input features like age, job, balance, education, and more. The best-performing model is saved and ready for cloud deployment (no UI).

---

## Problem Statement

Banks run marketing campaigns to encourage customers to make term deposits. The goal is to build a predictive model that can classify whether a customer will subscribe to the deposit based on their attributes.

---

## Features

- Dataset: Bank Marketing Dataset (`data.csv`, `test_data.csv`)
- Preprocessing: Label Encoding + Standard Scaling
- Models Trained:
  - Random Forest (Best performer)
  - XGBoost
  - Logistic Regression
  - Decision Tree
- Evaluation Metrics:
  - Accuracy, Precision, Recall, F1 Score, AUC
  - ROC Curve Comparison
- Model Export:
  - `deposit_rf_model.pkl`
  - `label_encoders.pkl`
  - `scaler.pkl`

---

## Files Included

| File                          | Description                                  |
|-------------------------------|----------------------------------------------|
| `data.csv`                   | Training dataset                             |
| `test_data.csv`              | Testing dataset                              |
| `training_and_evaluation.ipynb` | Complete training, evaluation, and saving pipeline |
| `deposit_rf_model.pkl`       | Trained Random Forest model                  |
| `label_encoders.pkl`         | Encoders for categorical variables           |
| `scaler.pkl`                 | Feature scaler used during training          |
| `README.md`                  | Project overview                             |

---

## Results Summary

| Model               | Accuracy | Precision | Recall | F1 Score | AUC     |
|--------------------|----------|-----------|--------|----------|---------|
| Random Forest     | 85.25%   | 82.53%    | 87.23% | 84.81%   | 91.36%  |
| XGBoost            | 84.83%   | 83.52%    | 84.57% | 84.04%   | 91.53%  |
| Logistic Regression| 80.00%   | 80.73%    | 75.72% | 78.15%   | 86.70%  |
| Decision Tree      | 76.29%   | 75.78%    | 73.20% | 74.47%   | 76.13%  |

---

## 🛠️ How to Use

1. Clone this repository  
2. Open `training_and_evaluation.ipynb` in Colab or Jupyter  
3. Run all cells to preprocess, train, evaluate, and export models  
4. The `.pkl` files are production-ready for inference pipelines

---




