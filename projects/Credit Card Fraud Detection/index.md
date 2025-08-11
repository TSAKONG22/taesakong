# Credit Card Fraud Detection

## Overview
A classification model to identify fraudulent credit card transactions, crucial for financial security.

## Dataset
- **Source:** Kaggle – Credit Card Fraud Detection dataset  
- **Size:** 284,807 transactions, with severe class imbalance (~0.17% fraud cases).  
- **Preprocessing:** Applied SMOTE oversampling, normalized numerical data.

## Approach
- Trained Random Forest, XGBoost, and Logistic Regression models.
- Focused on maximizing recall to catch fraudulent transactions while minimizing false positives.

## Results
- XGBoost achieved ROC-AUC of 0.99 and high recall.
- Model can be integrated into real-time fraud detection systems.

## Links
- [View Code in Repository](https://github.com/TSAKONG22/taesakong/tree/main/projects/credit-card-fraud-detection)  
- [← Back to Portfolio Home](/taesakong/)
