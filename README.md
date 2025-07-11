# 🔐 Phishing URL Detection using Machine Learning

This project aims to classify URLs as **phishing** or **legitimate** using machine learning models to enhance cybersecurity.

## 📁 Domain
Cyber Security

## 📊 Dataset Overview
- **Name:** URL Phishing Detection Dataset
- **Samples:** 10,000
- **Features:** 18 URL-based features (e.g., IP presence, URL length, domain age)
- **Missing/Null Values:** None
- **Preprocessing:** Feature scaling, handling imbalance, feature engineering

## 🎯 Objectives
1. Classify URLs as phishing or legitimate
2. Perform EDA and visualize trends
3. Train multiple ML models and compare results
4. Select the most accurate model (XGBoost)
5. Deploy model for real-time URL prediction

## ⚙️ Tools Used
- Python
- Pandas, NumPy, Scikit-learn, XGBoost
- Matplotlib & Seaborn (for visualization)

## 🧠 Models Evaluated
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- **XGBoost** (✅ Final selected model)

## 🚀 Features Used
- Have_IP, Have_At, URL_Length, Redirection, TinyURL, HTTPS, Domain_Age, Web_Traffic, etc.

## ✅ Final Model
- **XGBoost** achieved the highest accuracy and was selected for deployment.
- A URL prediction function analyzes an input URL and classifies it as **safe** or **not safe**.

## 🔍 Sample Prediction
```python
test_url = "http://www.accsystemprblemhelp.site/checkpoint.htm"
result = predict_url_safety(test_url)
print(result)
