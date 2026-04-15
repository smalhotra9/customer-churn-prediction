# 📊 Customer Churn Prediction

---

## 📌 Overview
Customer churn is one of the biggest challenges for subscription-based businesses. Predicting whether a customer will leave (churn) helps companies take proactive steps to improve retention and reduce revenue loss.  

This project builds a machine learning pipeline to predict customer churn using classification algorithms, along with data analysis and visualization to uncover key patterns influencing churn.

---

## 🎯 Objectives
- Analyze customer data to identify patterns related to churn  
- Perform data preprocessing and feature engineering  
- Train multiple machine learning models  
- Evaluate models using appropriate metrics  
- Select the best-performing model for churn prediction  
- Derive actionable business insights  

---

## 🗂️ Dataset
The dataset contains customer-related features such as:
- Demographics  
- Account information  
- Service usage details  
- Charges and tenure  

**Target Variable:**
- Churn (Yes/No)

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Handling missing values  
- Encoding categorical variables  
- Feature scaling  
- Train-test split  

### 2. Exploratory Data Analysis (EDA)
- Distribution of churn vs non-churn customers  
- Correlation analysis  
- Feature-wise impact on churn  
- Visualization using plots  

### 3. Model Selection
Multiple machine learning models were evaluated, including:
- Logistic Regression  
- Decision Trees  
- KNN  
- SVM  
- Random Forest  
- XGBoost  

Final models were selected based on performance and generalization ability:
- Logistic Regression (baseline)  
- Random Forest  
- XGBoost  

(Other models were excluded due to comparatively lower performance or lack of improvement)

---

## 📈 Model Evaluation
Evaluation metrics used:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

### ⭐ Key Result
**Logistic Regression achieved the highest recall, making it the most suitable model for identifying customers likely to churn.**

---

## 📊 Results & Insights
- Customers with low tenure are more likely to churn  
- Higher monthly charges correlate with higher churn  
- Certain services significantly influence retention  
- Model comparison helped identify the best predictive approach  

---

## 🚀 Tech Stack

**Programming Language:**
- Python  

**Libraries Used:**
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
