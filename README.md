# 💳 Credit Card Fraud Detection & Risk Analytics Dashboard

## 📌 Overview

This project presents an end-to-end fraud detection system using **data analysis, machine learning, and interactive Tableau dashboards**.

It focuses on identifying fraudulent transactions from highly imbalanced data and providing actionable insights through visualization.

---

## 🎯 Objectives

* Detect fraudulent transactions using machine learning
* Handle class imbalance effectively
* Compare multiple classification models
* Visualize fraud patterns and model performance
* Build an interactive fraud monitoring dashboard

---

## 📊 Dashboards

### 1️⃣ Fraud Monitoring Overview

* Total transactions and fraud cases
* Fraud rate (~0.17%)
* Fraud distribution by risk level
* Fraud capture effectiveness
* Fraud trends by time of day and transaction amount

---

### 2️⃣ Fraud Risk Intelligence

* Fraud probability distribution (XGBoost)
* Risk segmentation (Low / Medium / High)
* Fraud rate by transaction amount
* Fraud rate by time of day
* Behavioral fraud insights

---

### 3️⃣ Model Performance Analysis

* Model comparison across multiple algorithms
* Fraud detection vs missed fraud
* Precision, Recall, and F1-score analysis
* False positives and operational impact

---

## 🤖 Machine Learning Pipeline

### Models Tested

* Logistic Regression
* Decision Tree
* Random Forest
* **XGBoost (Best Performing Model)**

---

### Data Preprocessing

* Train-Test Split
* Feature Scaling using **StandardScaler**
* Handling class imbalance using:

  * Undersampling
  * Oversampling
  * **SMOTE (Selected Final Approach)**

---

### Why SMOTE?

The dataset is highly imbalanced (~0.17% fraud), so SMOTE was used to:

* Generate synthetic fraud samples
* Improve model learning
* Increase recall for fraud detection

---

### Final Model

**XGBoost was selected because:**

* Best fraud detection performance
* Strong separation between fraud and non-fraud
* Higher precision-recall balance
* Better handling of complex patterns

---

## 📈 Key Insights

* Fraud cases are extremely rare (~0.17%)
* High-risk transactions capture the majority of fraud
* Fraud probability distribution shows strong model separation
* Fraud activity is higher during **morning and night periods**
* Transaction amount influences fraud likelihood

---

## 🔄 Interactivity Features

* Dashboard-wide filtering (click-to-filter)
* Toggle switch: **All Transactions vs Fraud Only**
* Risk level filtering
* Multi-dashboard navigation
* Interactive exploration of fraud patterns

---

## 🛠️ Tools & Technologies

* **Tableau** → Dashboard & visualization
* **Python (Scikit-learn, XGBoost)** → Model building
* **SMOTE (Imbalanced-learn)** → Data balancing
* **Pandas, NumPy** → Data processing
* **GitHub** → Project hosting

---

## 📷 Project Preview

Overview: https://github.com/Devdat27/credit_card_fraud_detection/blob/main/images/Overview%20Dashboard.png


---

## 🌐 Tableau File Link

👉 *(Add your Tableau File link here)*

---

## 🚀 How to Use

1. Open the Tableau Public dashboard
2. Navigate through dashboards using buttons
3. Use filters and toggles to explore fraud patterns
4. Analyze model performance and risk insights

---

## 📌 Future Improvements

* Real-time fraud detection system
* Deployment using Streamlit / Flask
* Advanced anomaly detection models
* Feature engineering for behavioral patterns

---

## 👤 Author

**Devansh Saxena**
Data Analytics Project

---

## ⭐ Acknowledgements

* Public credit card fraud dataset
* Tableau for visualization
* XGBoost & Scikit-learn for ML models

---
