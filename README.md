# Titanic Survival Prediction

This project implements an end-to-end machine learning pipeline to predict whether a passenger survived the Titanic disaster.

## Dataset
- Titanic dataset (Kaggle)

## Approach
- Train-test split with stratification
- Separate preprocessing for numerical and categorical features
- Handling missing values
- One-hot encoding
- Logistic Regression as baseline model
- Random Forest for improved performance

## Evaluation
- Confusion Matrix
- Classification Report
- ROC-AUC score
- Feature importance analysis

## Key Insights
- Gender and passenger class were the most important predictors
- Fare and age also contributed significantly
- High-cardinality features like Name and Ticket had little impact

## Tools Used
- Python
- pandas
- scikit-learn
- Numpy
