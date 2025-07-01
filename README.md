# Customer Churn Prediction 📉

A professional machine learning pipeline to predict customer churn for a subscription-based service using the Telco dataset.

## 🔍 Project Goals

- Predict customer churn
- Handle imbalanced dataset
- Maximize business KPIs: precision & recall

## 📦 Model Used

- XGBoost (optimized with SMOTE & threshold tuning)

## 📈 Metrics

| Metric    | Value (Approx.) |
|-----------|-----------------|
| Accuracy  | 85–89%          |
| Precision | 60–75%          |
| Recall    | 70–80%          |
| ROC AUC   | ~0.85           |

## 💾 Files

- `Customer_Churn_Prediction.ipynb`: Main notebook
- `xgboost_optimized_model.pkl`: Saved trained model

## ✅ Dataset

Kaggle: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
