# Customer Churn Prediction 📊

This project analyzes customer churn using the Telco dataset and builds a logistic regression model to predict which customers are at risk of leaving.

## 🔍 Problem Statement
A telecom company is experiencing high customer churn. The goal is to:
- Analyze customer behavior
- Identify features influencing churn
- Predict churn using logistic regression

## 📂 Dataset Info
- Rows: 7043 customer records
- Features: 21 (e.g., tenure, billing, services)
- Target: Churn (Yes/No)

## 📈 Key Steps
- Data cleaning (e.g., TotalCharges column)
- Encoding categorical variables
- Logistic Regression modeling
- Churn driver analysis via coefficients

## 💡 Key Insights
- **Tenure**: New customers are more likely to churn
- **Fiber Optic users** show higher churn risk
- **High TotalCharges** → more likely to churn

## ✅ Outcome
A lightweight logistic regression model was built with ~79% accuracy.  
The model and insights help prioritize retention strategies.

## 🛠️ Tools Used
- Python (Pandas, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook
