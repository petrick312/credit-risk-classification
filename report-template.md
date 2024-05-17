# Module 20 Report - Credit Risk Analysis

## Overview of the Analysis

* The purpose of this analyais was to determine the credit risk for 'healthy' loans and for 'high risk loans'.
* The models predict the credit worthiness of individuals based on their credit risk.
* The overall accurracy and precision were attempted to be predicted from the trained models.
* The following steps here followed:
  - The data was read into a dataframe from the given csv file. 
  - Created labels set (y) from the “loan_status” column, and then created the features (X) DataFrame from the remaining columns.
  - The data was split into train and test pools utilizing train_test_split.  
  - A logistic regression model was fit using the training data (X_train and y_train).
  - Predictions for the testing data lables were saved using the testing feature data (X_test) and the fitted model. 
  - Then evaluated the models performance by generating a confusion maatrix and printing the classification report. 

## Results

* Description of Model 1 Accuracy, Precision, and Recall scores. 
  - Overall accuracy of the model is at 99% which is very high. 
  - Precision is at 100% for healthy loans and 85% for high risk loans.
  - Recall is at 99% for healthy loans and 95% for high risk loans.
  - The model is able to predict healthy loans very well but the high risk loans a little less successfully.

## Summary

* With an overall score of 99% for accuracy, 100% for precision and 99% for recall, this model seems to predict healthy loans well. However, there should be an understanding that the predication of high risk loans is not accurate with enough precision to warrant giving the loan. This is especially true given the loans are considered high risk in the first place.
