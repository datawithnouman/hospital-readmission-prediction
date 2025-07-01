# 🏥 Hospital Readmission Prediction - ML Project

This project builds a machine learning model to predict whether diabetic patients will be readmitted to the hospital within 30 days of discharge, using real-world hospital data from 130+ U.S. hospitals between 1999–2008.

---

## 🔍 Problem Statement

Hospital readmissions are expensive and often preventable. Predicting which patients are at high risk of readmission can help improve care and reduce cost.

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008)
- **Records**: 100,000+ unique hospital visits
- **Target**: Whether the patient was readmitted within 30 days (`<30` vs. others)

*Dataset not included due to size — please download manually if replicating.*

---

## ⚙️ Tools Used

- Python (Pandas, Numpy, Seaborn, Scikit-learn, Matplotlib)
- Google Colab
- Random Forest Classifier
- Feature engineering + preprocessing

---

## 📊 Exploratory Data Analysis

- Missing value treatment
- Patient age, time in hospital, insulin levels, and number of lab procedures had the strongest signal

---

## 🧠 Model Building

- Random Forest classifier selected after comparing several models
- Stratified train-test split to maintain class balance
- Key performance metrics:
  - **Precision**: 0.67
  - **Recall**: 0.70
  - **Accuracy**: ~89%

---

## 🔎 Results

### 🔹 Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

### 🔹 Feature Importance

![Feature Importance](images/feature_importance.png)

---

## ✅ Key Learnings

- Class imbalance required careful metric selection (recall > accuracy)
- Hospital length of stay and number of lab procedures were the most predictive features
- Feature engineering improved signal in multiple variables (age, insulin, procedures)

---

## 💡 About Me

**Nouman Kabir**  
Undergraduate @ Georgia State University  
Aspiring Data Analyst 
 GPA: 3.78 | President's List Spring 2025  

