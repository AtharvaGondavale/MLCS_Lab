# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project focuses on building a Machine Learning model to detect fraudulent credit card transactions using binary classification. The objective is to classify transactions as either legitimate or fraudulent based on transaction-level features.

Fraud detection is a critical cybersecurity application that helps financial institutions reduce monetary losses and protect customers from unauthorized transactions.

## Problem Statement

Develop a machine learning model that classifies credit card transactions as fraudulent or legitimate with at least 90% accuracy and high recall to minimize missed fraud cases.

## Dataset

- Source: Kaggle Credit Card Fraud Detection Dataset
- Format: CSV
- Target Variable:

  0 → Legitimate Transaction
  
  1 → Fraudulent Transaction

The dataset contains anonymized numerical features along with transaction amount and time.

## Methodology

### 1. Data Loading and Exploration

### 2. Data Preprocessing

- Handling class imbalance
- Feature scaling

### 3. Model Training

- Logistic Regression
- Decision Tree
- Random Forest

### 4. Model Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Evaluation Metrics

Since fraud datasets are highly imbalanced, emphasis is placed on:

- Recall (to detect maximum fraud cases)
- Precision (to reduce false alarms)
- F1-score (balance between precision and recall)

## Expected Impact

- Improved fraud detection accuracy
- Reduced financial losses
- Automated transaction monitoring
- Enhanced cybersecurity posture

## Future Improvements

- Use advanced models such as XGBoost
- Implement SMOTE for class imbalance handling
- Deploy model as a real-time API
- Explore anomaly detection techniques
