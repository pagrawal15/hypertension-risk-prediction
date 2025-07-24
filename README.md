# hypertension-risk-prediction

# 🫀 Hypertension Risk Prediction using Multi-Hospital Patient Data

This project uses anonymized patient data from four hospitals to build machine learning models that predict the risk of hypertension. The goal is to assist healthcare professionals in early identification of high-risk individuals and support preventative care.

> 📊 Built with: Logistic Regression, Random Forest, XGBoost  
> 📈 Explainability: Feature Importance & SHAP  
> 📁 Dataset: [Kaggle - Common Heart Disease Data (4 Hospitals)](https://www.kaggle.com/datasets/denysskyrda/common-heart-disease-data-4-hospitals)

---

## 🧠 Problem Statement

Hypertension is a leading risk factor for cardiovascular diseases. Early prediction using clinical and demographic data can reduce hospitalization and long-term complications. This project builds and compares multiple ML models to identify patients at high risk.

---

## 🗃️ Dataset Overview

- **Source:** Kaggle  
- **Observations:** 4 hospitals' anonymized patient records  
- **Features include:**  
  - Age, Sex  
  - Resting Blood Pressure  
  - Cholesterol Level  
  - Chest Pain Type  
  - Fasting Blood Sugar  
  - Heart Rate Metrics  
- **Target variable:** `hypertension` (binary: 0 = No, 1 = Yes)

---

## 📈 Methodology

### 1. Exploratory Data Analysis (EDA)
- Distribution of variables across hospitals
- Correlation matrix
- Class imbalance analysis
- Feature relationship with `hypertension`

### 2. Modeling
- Logistic Regression (Baseline)
- Random Forest Classifier
- XGBoost Classifier

### 3. Evaluation
- Accuracy, Precision, Recall
- ROC-AUC Scores
- Confusion Matrices

### 4. Explainability
- Feature importance plots
- SHAP summary plot
- SHAP force plot for individual prediction

---

## 🏆 Results Summary

| Model              | Accuracy 
|-------------------|---------
| Logistic Regression | ~99%     
| Random Forest       | ~81%     
| XGBoost             | ~97%   

✅ **Best Model:** XGBoost  
🔍 **Top Features:** Age, Resting BP, Chest Pain Type, Cholesterol


