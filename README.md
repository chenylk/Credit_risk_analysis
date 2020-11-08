# Credit_risk_analysis

## Overview
* The purpose of this project was to analyze the effects of different machine learning sampling techniques. 

## Results
* The naive random oversampling model gave an accuracy score of .65, with a precision and recall score of .01 and .74, respectively.

![naive_oversample](https://github.com/chenylk/Credit_risk_analysis/blob/main/naive_random_oversampling.PNG).

* The SMOTE oversampling model gave an accuracy score of .66, with a precision and recall score of .01 and .63, respectively.

![smote_oversample](https://github.com/chenylk/Credit_risk_analysis/blob/main/smote_oversampling.PNG).

* The Cluster Centroids undersampling model gave an accuracy score of .54, with a precision and recall score of .01 and .67, respectively. 

![cluster_undersample](https://github.com/chenylk/Credit_risk_analysis/blob/main/undersampling.PNG).

* The combination sampling model gave an accuracy score of .64, with a precision and recall score of .01 and .70, respectively

![combination](https://github.com/chenylk/Credit_risk_analysis/blob/main/comination.PNG).

* The Balanced Random Forest Classifier ensemble model gave an accuracy score of .77, with a precision and recall score of .03 and .68, respectively.

![balanced_random_forst](https://github.com/chenylk/Credit_risk_analysis/blob/main/balanced_random_forest.PNG).

* The easy ensemble adaboost classifier model gave an accuracy score of .93, with a precision and recall score of .09 and .92, respectively.

![adaboost](https://github.com/chenylk/Credit_risk_analysis/blob/main/adaboost.PNG).

## Summary
* The oversampling models outperformed the undersampling and combination models. In particular, the SMOTE produced the highest accuracy. However, the ensemble classifiers performed the best. The easy ensemble adaboost classifier produced an accuracy score of .93. This was the highest by far by about 14 percent. These ensemble classifiers produce better results because they simutaneously aggregate smaller model predictions to make a more accurate prediction. Future evaluation of data should be using these ensemble models to predict outcomes. 


