# credit-risk-classification

## Overview of the Analysis

This analysis model is built with the purpose of evaluating high vs. low-risk loan quality. The model considers the following variables:
* loan_size
* interest_rate
* borrower_income
* debt_to_income
* num_of_accounts   
* derogatory_marks
* total_debt

These variables are used to determine the safety of a loan and the probability of a loan being either low or high risk. The variables that the model predicts, high risk loans and low risk loans, are important for determining the creditworthiness of borrowers and the viability of new loans.

To create our model, a logistic regression method was used with the following steps:
* Split the data into training and testing datasets.
* Fit the model with the training data.
* Predict the outcome for the data.
* Create a confusion matrix and a classification model to determine the accuracy of the predictions.

## Results

* Machine Learning Model:
  * Description of Model Accuracy, Precision, and Recall scores.
  * Balanced accuracy: 0.9520479254722232
  * Healthy loan precision: 1.00
  * Healthy loan recall: 0.99
  * High-risk loan precision: 0.85
  * High-risk loan recall: 0.91

## Summary

In summary the model is trained to be able to identify healthy and high-risk loans. From the results section the model is much more accurate at determining safe loans rather than high-risk ones. Because high-risk loan precision is only 85% it is clear that when using this model there is a likely chance that it will misidentify a high-risk loan. However, it is very possible that we are not aiming to identify high-risk loans but safe ones which is what this model excels at. I highly recommend this model.

