# Credit_Risk_Analysis

## Overview
The purpose of this challenge was to experiment with a variety of different supervised machine learning models in order to see which one was most effective at predicting credit risk 

## Results

## Resampling Models to Predict Credit Risk
Employed imbalanced-learn and scikit-learn libraries to build and evaluate models with unbalanced classes
- Classification predicts the CATEGORY that data belongs to.
- Regression predicts a NUMERICAL value based on previously observed data.
### Oversampling
- Oversampling of Naive and with SMOTE did not yield a usable model
- Naive Random Oversampling As you can see below, the precision of our Naive Random test is quite high. It does not perform as well in recall, where it is only .64.
Naive oversampling imbalanced classification report

![imbalanced classification report_Naive_oversampling](https://user-images.githubusercontent.com/74462990/136706062-a580d22d-f9db-4ff2-a0fd-5ed26426bc3e.jpg)

SMOTE Oversampling imbalanced classification report
![SMOTE_oversampling_umbalanced classification_report](https://user-images.githubusercontent.com/74462990/136707697-aae1464e-775e-46f4-b2e5-719c3aeb42b9.jpg)

### Undersampling









## Conclusion:
Two evaluation methods: ensemble learning and re-sampling
Easy Ensemble AdaBoost Classifier performs the best with our steps & dataset; therefore, we would move forward with this estimator for further predictions.

The oversampling recall score (with SMOTE) has the highest score for predicting both low-risk and high risk loan statuses. We would put forward that this is the best model considering the financial cost risk associated with False Negatives.

Combination sampling
Generate a confusion matrix.
Print out the imbalanced classification report
