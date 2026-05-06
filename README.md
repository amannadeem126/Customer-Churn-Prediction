# Customer Churn Prediction — End-to-End ML Pipeline

Predicting customer churn using machine learning on the Telco Customer Churn dataset.

## Project Overview
- **Dataset:** Telco Customer Churn (Kaggle) — 7,043 records, 21 features
- **Goal:** Predict which customers are likely to churn and identify key retention drivers

## What's Covered
- Data cleaning & preprocessing (missing values, encoding, StandardScaler)
- Exploratory Data Analysis & statistical insights
- 4 ML models trained & compared: Logistic Regression, Decision Tree, Random Forest, ANN
- Best model: Logistic Regression — 80% accuracy, F1-score: 0.56
- K-Means clustering (k=3) for customer segmentation
- Model deployment as Flask REST API

## Tools Used
Python · Pandas · Scikit-learn · Matplotlib · Seaborn · Flask

## Key Findings
- Short tenure and high monthly charges are the strongest churn predictors
- Month-to-month contracts show significantly higher churn rates
- 3 customer segments identified: High-value long-term, New at-risk, Stable low-spend
