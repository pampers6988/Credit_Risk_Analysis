# Credit_Risk_Analysis

## Overview
The purpose of this challenge was to experiment with a variety of different supervised machine learning models in order to see which one was most effective at predicting credit risk 

## Results
### Credit Risk Resampling
- Oversampling of Naive and with SMOTE did not yield a usable model

-Naive Oversampling
- Balanced accuracy score: 0.6473707152052903


- Naive oversampling imbalanced classification report
  
![imbalanced classification report_Naive_oversampling](https://user-images.githubusercontent.com/74462990/136706062-a580d22d-f9db-4ff2-a0fd-5ed26426bc3e.jpg)


- SMOTE Oversampling
Balanced accuracy score:0.6621602612787003


SMOTE Oversampling imbalanced classification report
![SMOTE_oversampling_umbalanced classification_report](https://user-images.githubusercontent.com/74462990/136707697-aae1464e-775e-46f4-b2e5-719c3aeb42b9.jpg)


- ClusterCentroids
Balanced accuracy score: 0.5447339051023905

![undersampling_ClusterCentroids](https://user-images.githubusercontent.com/74462990/136713692-4d0eac94-14dd-495a-b28f-a05db0b6e893.jpg)

### Credit Risk Ensemble

- Balanced Random Forest Classifier

Balanced accuracy score: 0.7885466545953005

![Balanced Random Forest Classifier_imbalanced classification report](https://user-images.githubusercontent.com/74462990/136713962-6710f536-d719-4a66-b3bd-578d41efba84.jpg)



![Random_forest _feature_importance](https://user-images.githubusercontent.com/74462990/136713978-ec2e758b-0d23-4dd1-a45c-4b03b46be0db.jpg)


-Easy Ensemble AdaBoost Classifier

Balanced accuracy score: 0.9316600714093861



![Easy Ensemble AdaBoost Classifier_imbalanced_classification_report](https://user-images.githubusercontent.com/74462990/136714055-5a2570af-c732-41ae-9414-6fda15efd3c8.jpg)


## Summary
Two evaluation methods: ensemble learning and re-sampling
Easy Ensemble AdaBoost Classifier performs the best with our steps & dataset; therefore, we would move forward with this estimator for further predictions.
The oversampling recall score (with SMOTE) has the highest score for predicting both low-risk and high risk loan statuses. We would put forward that this is the best model considering the financial cost risk associated with False Negatives.

