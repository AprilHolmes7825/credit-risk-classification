# Module 12 Report Template

## Overview of the Analysis

* Purpose: Use various techniques to train and evaluate a model based on loan risk. Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

* Data: The financial data provided and used in the model included the following fields:
    loan amount, interest rate, borrower income, debt to income, number of accounts, derogatory marks,total debt,loan status (Healthy/High risk of defaulting)
    The model was trained to predict loan status
    
* The model was trained to predict loan status (Healthy/High risk of defaulting).

* Methods used: Logistic regression - a statistical method for predicting binary outcomes from data.

* Stages of the machine learning process

PREPROCESS
--Separate the data into labels and features
--Split the data into training and testing datasets by using `train_test_split`

TRAIN
--Create a Logistic Regression Model with the Original Data
--Fit a logistic regression model by using the training data

PREDICT
--Make a prediction using the testing data

VALIDATE
--Evaluate the model’s performance by doing the following:
    Generate a confusion matrix.
    Print the classification report.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy (99%), Precision (100% for healthy loans, 87% for high risk loans), and Recall scores (100% for healthy loans, 89% for high risk loans).

## Summary

* The model tested would is a good choice due to the high level of accuracy and recall predicting which loans will be healthy and which are at risk.  The accuracy and recall is slightly lower for predicting high-risk loans, but accuracy and recall above 70-80% is considered desirable and this  model surpasses that.  
* Which prediction is more important (predicting healthy vs high risk) depends on the reason for the analysis.  If the purpose of the analysis is to find customers for a solicitation effort, it's more important to predict what will be a healthy loan.  If the purpose of the analysis is to find customers for a pre-default outreach, it would be more important to accurately predict high-risk loans.
This model accounts for each.  
