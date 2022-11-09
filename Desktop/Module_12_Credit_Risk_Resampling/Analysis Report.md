# Module 12 Report 

## Overview of the Analysis

*The purpose of this anaylsis is to produce a model that will provide a binary answer (yes or no) whether a loan is healthy (low risk) or not healthy (high risk)
*The anaylsis was based on 77,536 loans that featured each of their loan size, interst rate, borrower income, debt to income ratio, quantity of loan accounts, derogatory marks and total debt.
*We are trying to assign a predictive outcome of future loan status. 
Summary of Analysis:
*First you must import the neccesary modules and libraries to perform the analysis.
*Import the lending data from a csv. 
*Label and then split the data into training and testing sets.
*Use the orginal data to create a fitted logistic regression model. Calculate the accuracy score, generate a confusion matrix and summarize the data with a classification report.
*Use the resampled data to create a fitted logistic regression model. Calculate the accuracy score, generate a confusion matrix and summarize the data with a classification report.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
                precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

Balanced Accuracy Score: 95%
Precision: 100% for low risk loans   Recall: 99% for low risk loans
           85% for high risk loans           91% for high risk


* Machine Learning Model 2

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384

Balanced Accuracy Score: 99%
Precision: 100% for low risk loans   Recall: 99% for low risk loans
           84% for high risk loans           99% for high risk


## Summary


The resampled logistic regression model is better able to predict riskier loans.

