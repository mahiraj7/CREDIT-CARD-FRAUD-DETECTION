# 💳 Credit Card Fraud Detection

An end-to-end Machine Learning project for detecting potentially fraudulent credit card transactions using **Isolation Forest-based anomaly detection**.

The project focuses on identifying unusual transaction patterns in a highly imbalanced dataset and provides a simple Streamlit interface for making fraud predictions.

---

## 🚀 Project Overview

Credit card fraud detection is a challenging Machine Learning problem because fraudulent transactions are extremely rare compared to legitimate transactions.

Instead of relying on a traditional binary classification approach, this project uses **Isolation Forest**, an unsupervised anomaly detection algorithm, to identify transactions that behave differently from the majority of the data.

### Key Objectives

- Detect potentially fraudulent transactions
- Identify unusual transaction patterns
- Handle highly imbalanced transaction data
- Perform data preprocessing and feature engineering
- Train an Isolation Forest anomaly detection model
- Save the trained model for inference
- Build an interactive Streamlit application

---

## 🧠 Machine Learning Approach

The overall workflow of the project is:

Transaction Dataset
        ↓
Data Preprocessing
        ↓
Feature Engineering
        ↓
Feature Preparation
        ↓
Isolation Forest
        ↓
Anomaly Detection
        ↓
Fraud / Normal Prediction
        ↓
Streamlit Application

CREDIT-CARD-FRAUD-DETECTION/
│
├── app.py
├── train.py
├── fraud_model.pkl
├── fraud_features.pkl
├── requirements.txt
├── README.md
└── .gitignore


Data Source link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
