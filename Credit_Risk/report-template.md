# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Purpose: Use various techniques to train and evaluate a model based on loan risk. Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
* Data: The financial data provided and used in the model included the following fields:
    loan amount, interest rate, borrower income, debt to income, number of accounts, derogatory marks,total debt,loan status (Healthy/High risk of defaulting)
    The model was trained to predict loan status
    
* The model was trained to predict loan status (Healthy/High risk of defaulting).

* Describe the stages of the machine learning process you went through as part of this analysis.
................
Separate the data into labels and features
Split the data into training and testing datasets by using `train_test_split`
Create a Logistic Regression Model with the Original Data
Step 1: Fit a logistic regression model by using the training data
Step 2: Make a prediction using the testing data....Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model.
Step 3: Evaluate the model’s performance by doing the following:
    Generate a confusion matrix.
    Print the classification report.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
?What is logistic regression?
Logistic regression is a statistical method for predicting binary outcomes from data.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy (99%), Precision, and Recall scores.

## Summary

Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning

For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
