# credit-risk-classification

# Data Analytics and Visualization Bootcamp - University of Toronto
# Module 20 Challenge 
# Date: September 24, 2024
# Name: Thet Win


## Overview of the Analysis

### Purpose of the Assignment
- The purpose of this assignment is to utilize various machine learning techniques to train and evaluate a model based on loan risk.

### Data 
- The target variable (to predict) is 'load_status' where 0 is defined to be 'Healthy Loan' and 1 is defined to be 'High=Risk Loan'.
- The dataset (lending_data.csv) consists of historical lending activity including:
  - loan_size
  - interest_rate
  - borrower_income
  - debt_to_income
  - num_of_accounts (Number of accounts that client holds)
  - total_debt
  
### Target Variable - Details
- The target variable ('load_status') has 75036 Healthy Loan (code 0) and 2500 High-Risk Loan (code 1)

### Steps
- Data engineering
  - Read the data file "lending_data.csv" and store it in Pandas DataFrame
  
- Create labels and assign target variable (y) and features (x)

- Split the data into training data and testing data by using the function train_test_split

### Methods Used
- The machine learning method used was Logistic Regression
- Fit the regression model using training data (X_train and y_train)
- Evaluate model's performance by creating a Confusion Matrix and Classification Report



## Results

- Logistic Regression Learning Model: Accuracy Score: 0.99
- Precision Scores: 1.00 (Healthy Loan) and 0.87 (High Risk Loan)

## Summary
The logistic regression model was able to produce predictions with high accuracy for both classes of the loans (Healthy Loan and High Risk Loan)

## Recommendation
The model produced a high accuracy predictions for both classes of the loans. To improve further, we could focus more on the data that pertains to High-Risk Loans since it slightly under performs compared to the Healthy Loan.


