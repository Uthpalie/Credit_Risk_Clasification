# Module 12 Report Template

## Overview of the Analysis

In this analysis we looked at the loans given to individual looking at data covering loan sizes, interest rates, borrower income, debt to income, number of accounts, total income and loan status. Here we looked at the loan status, whether it is 0, healthy loan or a 1, a high -risk loan and put this into a model and see if the model can correctly predict any new data. 

For this purpose we have selected the Logistic Regrassion Model and segregated the data as 75% train data to train the model and 25% test data to test the model so that we can compare the predicted results against actual.

## Results

By analysing the results of the Logistic Regression Model results, accuracy of the loan status is 99%, which is a very good percentage. The precision score of healthy loans is at 100%, however the high-risk loans its at 85%. This would mean that 15% of high-risk loans are not detected by the model. Looking at the recall score, you see that for healthy scores it's 99% and for high-risk loans this result is higher at 95%. As such it is an indication that although the precision score is low for high-risk loans the recall score is much higher with 95%. 

## Summary

The final results of Logistical Machine Learning model has provided good results showing 99% accuracy and good scores on precision, recall and f1 scores, especially for healthy loans. As the high-risk loan results are lower it is best to perform more tests with a selection of data to improve the model in order to improve the predictions of the high-risk loans as they have the biggest chances of loss for the organization.
