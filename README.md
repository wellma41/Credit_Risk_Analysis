# Credit_Risk_Analysis

## Overview

The purpose of this project was to compare the predictive capabilites of various models through the lens of credit risk.

## Results

Naive Random Oversamplingbalanced
- Accuracy score: 64.6%
- Precision High-risk/Low-risk 0.01/1.00 
- Recall High-risk/Low-risk 0.71/0.58


SMOTE Oversampling
- Accuracy score: 65.8%
- Precision High-risk/Low-risk 0.01/1.00 
- Recall High-risk/Low-risk 0.63/0.68


Undersampling
- Accuracy score: 54.5%
- Precision High-risk/Low-risk 0.01/1.00 
- Recall High-risk/Low-risk 0.60/0.40


Combination (Over and Under) 
- Accuracy score: 64.6%
- Precision High-risk/Low-risk 0.01/1.00 
- Recall High-risk/Low-risk 0.72/0.57


Balanced Random Forest
- Accuracy score: 76.6%
- Precision High-risk/Low-risk 0.03/1.00 
- Recall High-risk/Low-risk 0.65/0.88


Easy Ensemble AdaBoost Classifier
- Accuracy score: 91.2%
- Precision High-risk/Low-risk 0.07/1.00 
- Recall High-risk/Low-risk 0.89/0.93


## Summary

The Easy Ensemble performed the best by far with an accuracy score of 91% and leaving only 10 out of 91 high risk loans unidentified.
Next best was Balanced Forest and the rest performed rather similarly. Even in the best performing model, Easy Ensemble, there were still
well over 1000 low-risk loans that were falsely identified identified as high risk. I would recommend running the positively
identified "high-risk" loans through more rigorous analysis to ensure that they're indeed high-risk.