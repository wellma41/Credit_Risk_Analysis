# Credit_Risk_Analysis

## Overview

The purpose of this project was to compare the predictive capabilites of various models through the lens of credit risk.

## Results

Naive Random Oversamplingbalanced
- Accuracy score: 64.6%
- Precision High-risk/Low-risk 0.01/1.00 
- Recall High-risk/Low-risk 0.71/0.58

![Native Oversamp](https://user-images.githubusercontent.com/90660790/149614027-6fac4db1-5a9d-48ea-b141-b50bc844938a.PNG)


SMOTE Oversampling
- Accuracy score: 65.8%
- Precision High-risk/Low-risk 0.01/1.00 
- Recall High-risk/Low-risk 0.63/0.68

![SMOTE Over](https://user-images.githubusercontent.com/90660790/149614032-f4cd08ca-52f1-452c-bb46-0298aab8b553.PNG)


Undersampling
- Accuracy score: 54.5%
- Precision High-risk/Low-risk 0.01/1.00 
- Recall High-risk/Low-risk 0.60/0.40

![Under](https://user-images.githubusercontent.com/90660790/149614038-99749aed-0931-4454-8391-ec5278b99ac1.PNG)


Combination (Over and Under) 
- Accuracy score: 64.6%
- Precision High-risk/Low-risk 0.01/1.00 
- Recall High-risk/Low-risk 0.72/0.57

![Combo](https://user-images.githubusercontent.com/90660790/149614043-ced96574-bdd5-4656-865c-712f2f7b4e4f.PNG)


Balanced Random Forest
- Accuracy score: 76.6%
- Precision High-risk/Low-risk 0.03/1.00 
- Recall High-risk/Low-risk 0.65/0.88

![brf](https://user-images.githubusercontent.com/90660790/149614050-5a8be882-1023-40c7-8124-a7698d139a12.PNG)

Easy Ensemble AdaBoost Classifier
- Accuracy score: 91.2%
- Precision High-risk/Low-risk 0.07/1.00 
- Recall High-risk/Low-risk 0.89/0.93

![easy](https://user-images.githubusercontent.com/90660790/149614052-3dd130e9-098d-41da-96fe-369cd63450d8.PNG)


## Summary

The Easy Ensemble performed the best by far with an accuracy score of 91% and leaving only 10 out of 91 high risk loans unidentified.
Next best was Balanced Forest and the rest performed rather similarly. Even in the best performing model, Easy Ensemble, there were still
well over 1000 low-risk loans that were falsely identified identified as high risk. I would recommend running the positively
identified "high-risk" loans through more rigorous analysis to ensure that they're indeed high-risk.
