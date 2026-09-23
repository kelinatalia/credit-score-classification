# Credit Score Classification

## Overview
This project predicts a customer's credit score category (Poor, Standard, or Good) based on their financial and demographic data. The dataset has 50,000 rows and 28 columns, including income, number of loans, payment history, and more.

## Steps
- Data cleaning: fixed placeholder values, converted text columns to numbers, handled outliers with capping
- Exploratory data analysis: checked the distribution of credit scores and how payment behaviour and debt level affect credit score
- Feature engineering and encoding: label encoding, scaling with RobustScaler
- Modeling: trained Random Forest and XGBoost, tuned with GridSearchCV
- Evaluation: accuracy, recall, and F1-score on the test set
- Feature importance: found which factors matter most for credit score

## Result
Random Forest slightly outperformed XGBoost, with an F1-score of around 0.76. The most important features are Outstanding Debt and Interest Rate.

## Files
```
No_1.ipynb                      # Main notebook
Credis_Score_Dataset_B.csv      # Dataset
```

## Tech Stack
Python, pandas, numpy, scikit-learn, XGBoost, seaborn, matplotlib
