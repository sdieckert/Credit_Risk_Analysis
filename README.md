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

![Naive Random Oversampling](https://user-images.githubusercontent.com/87085239/184518477-96c0b947-99d5-4221-ad68-647cc681c197.png)

- Balance Accuracy Score: 0.6366972052004142
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .62/.65 

### SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/87085239/184518482-1ffe491c-02b9-4f2a-b283-a833631ccbd6.png)

- Balance Accuracy Score: 0.6302712208564487
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .62/.64 

### Undersampling

![Undersampling](https://user-images.githubusercontent.com/87085239/184518493-9212b353-7609-46fe-a77b-8e9cfa9c2c8b.png)

- Balance Accuracy Score: 0.5293318990697431
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .61/.45

## Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

### Combination (Over and Under) Sampling

![Over and Under Sampling](https://user-images.githubusercontent.com/87085239/184518504-62fdec11-320b-4739-a28a-c9ab092aebb4.png)

- Balance Accuracy Score: 0.5293318990697431
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .71/.59


## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

### Balance Random Forest Classifer

![Random Forest](https://user-images.githubusercontent.com/87085239/184518511-88f95def-63c4-4cca-8f8d-c935beccd95f.png)

- Balance Accuracy Score: 0.7699139915160833
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .66/.88

### Easy Ensemble AdaBoost Classifer

![Ensemble AdaBoost](https://user-images.githubusercontent.com/87085239/184518522-dcdb4730-eaef-46ab-8c6f-c78607d36eca.png)

- Balance Accuracy Score: 0.9316600714093861
- Precision:Precision is low for high_risk and high for low_risk.
- Recall: High/Low risk = .92/.94




## Summary

All the models score about the same of the Precision test. A better indictor of how well the models are able to perform on test and new data is the sensitity or recall score. This is a measure of how many transactions that were fradulant, were correctly identified. The accuracy score closer to 1 is the best machine learning model. 

Comparing the balance accuracy score and the recall score of all the models results in the Easy Ensemble AdaBoost Classifer as the best machine learning model for this particular dataset. 





