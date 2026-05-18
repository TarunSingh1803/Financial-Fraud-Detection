# AI-Powered Fraud Detection System Using Machine Learning

## Overview
The AI-Powered Fraud Detection System is a machine learning project developed to detect fraudulent financial transactions using classification algorithms. The system analyzes transaction data and predicts whether a transaction is genuine or fraudulent.

This project demonstrates the practical application of machine learning in financial security and fraud prevention.

---

# Features
- Fraudulent transaction detection
- Data preprocessing and feature scaling
- Imbalanced data handling using SMOTE
- Logistic Regression and Random Forest models
- Model evaluation using multiple metrics
- ROC-AUC score analysis
- Feature importance visualization
- Model saving and loading

---

# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

# Dataset
Dataset Used:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Information
- Total Transactions: 284,807
- Fraudulent Transactions: 492
- Genuine Transactions: 284,315

### Target Variable
- Class = 0 → Genuine Transaction
- Class = 1 → Fraudulent Transaction

---

# Project Workflow
1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis(EDA)
4. Feature Scaling
5. Handling Imbalanced Data using SMOTE
6. Model Training
7. Model Evaluation
8. Fraud Prediction
9. Model Saving

---

# Machine Learning Models Used

## Logistic Regression
Used as a baseline model for classification.

## Random Forest Classifier
Used for improved fraud detection accuracy.

---

# Evaluation Metrics
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

# Project Structure

```bash
AI-Powered-Fraud-Detection-System/
│
├── data/
│   └── creditcard.csv
│
├── notebooks/
│   └── fraud_detection.ipynb
│
├── models/
│   └── fraud_detection_model.pkl
│
├── README.md
│
└── requirements.txt
