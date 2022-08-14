# Credit_Risk_Analysis

## Project Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we'll be employing different techniques to train and evaluate models with unbalanced classes. 


## Resources
- Data Source: LoanStats_2019Q1.csv
- Python Libraries: 
    - imbalance-learn
    - scikit-learn
- Machine Learning Models
    - RandomOverSampler
    - SMOTE
    - ClusterCentroids
    - SMOTEEN
  

## Deliverable 1: Use Resampling Models to Predict Credit Risk

Evaluate three machine learning models by using resampling to determine which is better at predicting credit risk.

### Naive Random Oversampling

- Balance Accuracy Score: 0.6366972052004142
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .62/.65 

### SMOTE Oversampling

- Balance Accuracy Score: 0.6302712208564487
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .62/.64 

### Undersampling

- Balance Accuracy Score: 0.5293318990697431
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .61/.45

## Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

### Combination (Over and Under) Sampling

- Balance Accuracy Score: 0.5293318990697431
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .71/.59


## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

### Balance Random Forest Classifer

- Balance Accuracy Score: 0.7699139915160833
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .66/.88

### Easy Ensemble AdaBoost Classifer

- Balance Accuracy Score: 0.9316600714093861
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .92/.94




## Summary

All the models score about the same of the Precision test. A better indictor of how well the models are able to perform on test and new data is the sensitity or recall score. This is a measure of how many transactions that were fradulant, were correctly identified. The accuracy score closer to 1 is the best machine learning model. 

Comparing the balance accuracy score and the recall score of all the models results in the Easy Ensemble AdaBoost Classifer as the best machine learning model for this particular dataset. 





