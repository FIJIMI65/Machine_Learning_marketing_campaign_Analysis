# 🎯 Marketing Campaign Analysis with Machine Learning



## 📘 Overview

This project aims to **predict customer responses to a bank’s marketing campaign** using machine learning. By identifying key customer characteristics and behaviors, the model helps improve targeting strategies, marketing efficiency, and overall campaign ROI.

> **Use Case**: Predict whether a customer will subscribe to a term deposit based on demographic and interaction data.

---

## 📌 Objectives

- 🎯 Maximize term deposit subscriptions
- 📈 Improve marketing efficiency and targeting
- 🤖 Apply machine learning models to predict customer response
- 💡 Extract actionable insights for decision-making

---

## 🧾 Dataset Summary

- **Records**: 11,163
- **Features**: 17 (including demographics, campaign interaction, financial status)
- **Target Variable**: `deposit` (Yes/No)

### 🔑 Key Features

- **Demographics**: `age`, `job`, `marital`, `education`
- **Financial Status**: `balance`, `loan`, `housing`
- **Campaign Details**: `campaign`, `contact`, `pdays`, `previous`, `poutcome`
- **Target**: `deposit` – whether the customer subscribed

---

## 🧪 Project Workflow

📊 1. Business Understanding
📚 2. Data Understanding
🧹 3. Data Cleaning & Preprocessing
📈 4. Exploratory Data Analysis (EDA)
🛠️ 5. Feature Engineering
🤖 6. Model Building & Evaluation
📌 7. Insights & Recommendations


## 🤖 Models Used

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- K-Nearest Neighbors (KNN)

### 📏 Evaluation Metrics

- Accuracy
- Precision / Recall / F1-Score
- AUC-ROC Curve
- Confusion Matrix

---

## 🚀 Results Snapshot

- **Best Model**: XGBoost
- **Accuracy**: 86%
- **AUC-ROC**: 0.91
- **Key Predictors**: Contact month, campaign outcome, previous contacts, duration

---

## 🛠️ Tech Stack

| Tool/Library       | Purpose                      |
|--------------------|------------------------------|
| `Python 3.9`       | Core programming language     |
| `Pandas / NumPy`   | Data manipulation             |
| `Matplotlib / Seaborn` | Data visualization        |
| `Scikit-learn`     | ML modeling & evaluation      |
| `XGBoost`          | Advanced ensemble learning    |
| `Jupyter Notebook` | Project development platform  |

---
