# Credit_Risk_Analysis

## Overview
The purpose of this challenge was to experiment with a variety of different supervised machine learning models in order to see which one was most effective at predicting credit risk 

## Results
### Oversampling
- Oversampling of Naive and with SMOTE did not yield a usable model
- Naive oversampling imbalanced classification report
  Balanced accuracy score: 0.6473707152052903

![imbalanced classification report_Naive_oversampling](https://user-images.githubusercontent.com/74462990/136706062-a580d22d-f9db-4ff2-a0fd-5ed26426bc3e.jpg)


- SMOTE Oversampling
Balanced accuracy score:0.6621602612787003

SMOTE Oversampling imbalanced classification report
![SMOTE_oversampling_umbalanced classification_report](https://user-images.githubusercontent.com/74462990/136707697-aae1464e-775e-46f4-b2e5-719c3aeb42b9.jpg)

### Undersampling
- ClusterCentroids
Balanced accuracy score: 0.5447339051023905

![undersampling_ClusterCentroids](https://user-images.githubusercontent.com/74462990/136713692-4d0eac94-14dd-495a-b28f-a05db0b6e893.jpg)


## Conclusion:
Two evaluation methods: ensemble learning and re-sampling
Easy Ensemble AdaBoost Classifier performs the best with our steps & dataset; therefore, we would move forward with this estimator for further predictions.
The oversampling recall score (with SMOTE) has the highest score for predicting both low-risk and high risk loan statuses. We would put forward that this is the best model considering the financial cost risk associated with False Negatives.

