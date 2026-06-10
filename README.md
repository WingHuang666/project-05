# project-05

# Loan Interest Rate Prediction

## Project Overview

This project analyzes borrower demographics, financial characteristics, and loan information to understand the factors that influence loan interest rates and to build machine learning models for interest rate prediction.

The study combines exploratory data analysis, correlation analysis, feature importance evaluation, and predictive modeling to identify key drivers of loan interest rates.

## Dataset

The dataset contains 45,000 loan records with the following features:

* Age
* Gender
* Education
* Person Income
* Employee Experience
* Home Ownership
* Loan Amount
* Loan Intent
* Loan Interest Rate
* Loan Percentage

Target Variable:

* Loan Interest Rate

## Research Questions

1. What factors influence loan interest rates?
2. Can borrower and loan characteristics accurately predict loan interest rates?
3. Which features are most important in determining interest rates?

## Methods

### Exploratory Data Analysis (EDA)

* Distribution analysis
* Categorical feature analysis
* Correlation analysis
* Outlier identification

### Machine Learning Models

* Linear Regression
* Ridge Regression
* Random Forest Regressor
* Gradient Boosting Regressor

### Evaluation Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

## Key Findings

* Home ownership showed the strongest categorical relationship with interest rates.
* Loan Amount and Loan Percentage had the highest positive correlations with interest rates.
* Person Income was identified as the most important feature by the Random Forest model.
* Random Forest achieved the best performance among all tested models.

## Model Performance

| Model             | R²    |
| ----------------- | ----- |
| Random Forest     | 0.097 |
| Gradient Boosting | 0.065 |
| Linear Regression | 0.043 |
| Ridge Regression  | 0.043 |

## Conclusion

The analysis found that borrower income, loan amount, age, employment experience, and loan percentage contribute to loan interest rate prediction. However, model performance remained relatively low, suggesting that important lending variables such as credit score, repayment history, and debt-to-income ratio are not included in the dataset. As a result, the dataset provides useful insights but is insufficient for highly accurate interest rate prediction.

## Tools

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn


