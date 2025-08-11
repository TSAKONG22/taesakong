# Big Mart Sales Prediction

## Overview
This project predicts product sales across different Big Mart outlets using machine learning regression models.  
The goal is to help retailers improve inventory management, plan promotions, and forecast demand more accurately.

## Dataset
- **Source:** Kaggle – Big Mart Sales dataset  
- **Size:** 8,523 records, 12 features (Item Type, Item MRP, Outlet Size, Item Visibility, etc.)  
- **Preprocessing:** Missing values imputed, categorical variables encoded, numerical features normalized, and interaction features engineered.

## Approach
- Conducted Exploratory Data Analysis (EDA) to identify trends and correlations.
- Trained and compared Linear Regression, Random Forest Regressor, and Gradient Boosting models.
- Tuned hyperparameters with GridSearchCV and applied cross-validation.

## Results
- Best model: Gradient Boosting with R² = 0.87 and RMSE = 1,132.
- Key predictors: Item MRP and Outlet Type.

## Links
- [View Code in Repository](https://github.com/TSAKONG22/taesakong/tree/main/projects/big-mart-sales-prediction)  
- [← Back to Portfolio Home](/taesakong/)
