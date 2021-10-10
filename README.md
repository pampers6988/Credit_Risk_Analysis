# Credit_Risk_Analysis

## Overview
The purpose of this challenge was to experiment with a variety of different supervised machine learning models in order to see which one was most effective at predicting credit risk 

## Results


### Credit Risk Resampling

- Naive Oversampling
  Balanced accuracy score: 0.6473707152052903
  

  Naive oversampling imbalanced classification report
  
 ![imbalanced classification report_Naive_oversampling](https://user-images.githubusercontent.com/74462990/136706062-a580d22d-f9db-4ff2-a0fd-5ed26426bc3e.jpg)


- SMOTE Oversampling
  Balanced accuracy score: 0.6621602612787003


  SMOTE Oversampling imbalanced classification report
 ![SMOTE_oversampling_umbalanced classification_report](https://user-images.githubusercontent.com/74462990/136707697-aae1464e-775e-46f4-b2e5-719c3aeb42b9.jpg)


- ClusterCentroids Undersampling
  Balanced accuracy score: 0.5447339051023905

  ClusterCentroids Undersampling imbalanced classification report
 ![undersampling_ClusterCentroids](https://user-images.githubusercontent.com/74462990/136713692-4d0eac94-14dd-495a-b28f-a05db0b6e893.jpg)

- Combination (Over and Under) Sampling
  Balanced accuracy score: 0.6461047268197353
  
  Combination (Over and Under) Sampling imbalanced classification report
  
  ![Combination _Over and Under)_Sampling_imbalanced_classification_report](https://user-images.githubusercontent.com/74462990/136714418-1b4e4283-69d6-4430-bfe3-9f1675ecb455.jpg)


### Credit Risk Ensemble
The performance of Random Forest Classifier, with and without AdaBoost did not perform well. The F1 scores were low for both due to a low precision or recall.

- Balanced Random Forest Classifier

  Balanced accuracy score: 0.7885466545953005

 ![Balanced Random Forest Classifier_imbalanced classification report](https://user-images.githubusercontent.com/74462990/136713962-6710f536-d719-4a66-b3bd-578d41efba84.jpg)



 ![Random_forest _feature_importance](https://user-images.githubusercontent.com/74462990/136713978-ec2e758b-0d23-4dd1-a45c-4b03b46be0db.jpg)


- Easy Ensemble AdaBoost Classifier

  Balanced accuracy score: 0.9316600714093861



 ![Easy Ensemble AdaBoost Classifier_imbalanced_classification_report](https://user-images.githubusercontent.com/74462990/136714055-5a2570af-c732-41ae-9414-6fda15efd3c8.jpg)


## Summary
Credit Risk Resampling machine learning models predictive ability to predict bad loans is inadquate and not recommended for use based on the low precision and F1 scores.
Credit risk ensemble machine learning similarly yeidled low precision and F1 scores, noting that random forest classifier withAdaBoost did a bit better than without.


  

