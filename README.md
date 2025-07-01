# 📊 Customer Churn Prediction

A professional machine learning pipeline to predict **customer churn** for a subscription-based service using the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

---

## 🚀 Project Objectives

- Predict customer churn (binary classification)
- Handle imbalanced datasets with SMOTE
- Focus on business-critical metrics: **Precision & Recall**
- Optimize XGBoost with feature engineering and threshold tuning

---

## 📁 Dataset

Dataset is downloaded from Kaggle using:

```bash
!mkdir -p ~/.kaggle
!mv kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json

!kaggle datasets download blastchar/telco-customer-churn
!unzip telco-customer-churn.zip
```

---

## 📦 Models Used

- ✅ Logistic Regression (baseline)
- ✅ Random Forest
- ✅ XGBoost (optimized)

---

## 📈 Model Performance

| Metric    | Value (Approx.) |
|-----------|-----------------|
| Accuracy  | 85–89%          |
| Precision | 60–75%          |
| Recall    | 70–80%          |
| ROC AUC   | ~0.85           |

> **Note:** Precision and recall are prioritized over raw accuracy for business impact.

---

## 📂 Files

- `Customer_Churn_Prediction.ipynb` – Full notebook with all steps
- `xgboost_optimized_model.pkl` – Saved model file
- `requirements.txt` – Python dependencies

---

## 📌 How to Run

1. Clone the repo or open in Colab
2. Upload your `kaggle.json` file
3. Run all cells in `Customer_Churn_Prediction.ipynb`

---

## 🛠️ Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 👤 Author

- Your Name ([@MazenAhmedAbdalmohsen](https://github.com/yourgithubhandle))

---
