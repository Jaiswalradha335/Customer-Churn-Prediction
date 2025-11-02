# Customer Churn Prediction (Telco / Amazon-style)

## Overview
End-to-end machine learning project to predict customer churn using the Telco Customer Churn dataset. Includes data preprocessing, handling class imbalance with SMOTE, model comparison (Logistic Regression and Random Forest), feature importance analysis, and simple business insights.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn (SMOTE), Matplotlib, Seaborn, KaggleHub, Joblib

## What I did
- Downloaded dataset directly from Kaggle via KaggleHub for reproducibility.  
- Cleaned and encoded categorical features; handled missing values.  
- Scaled features and used SMOTE to balance the training data.  
- Trained and compared Logistic Regression and Random Forest classifiers.  
- Evaluated models with accuracy, ROC-AUC, confusion matrix, and cross-validation.  
- Extracted top features influencing churn and produced actionable business insights.

## How to run
1. Open `customer_churn_colab.ipynb` in Google Colab.  
2. Run the cells in order. Install dependencies if prompted:
