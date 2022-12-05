# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to use supervised machine learning to evaluate and predict credit risk. We are using python and various plugins such as scikitlearn and imbalanced learn. Using these tools we can import our data, that has more good loans than bad loans, and use different models to predict future outcomes. the models we are using are RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier.

## Results

### OverSampling

Over sampling (RandomOverSampler)
  - Balanced accuracy score of 64%
  - percision score of 99%
  - recall score of 60%
![image](https://user-images.githubusercontent.com/109539205/205724270-d0d734fb-5321-49dd-8186-c842cf73caa7.png)

Over sampling (SMOTE)
  - Balanced accuracy score of 66%
  - percision score of 99% 
  - recall score of 69%
![image](https://user-images.githubusercontent.com/109539205/205722796-18a76240-cba7-4cf9-b56e-757b7201b050.png)

### Undersampling

Undersampling (SMOTE)
  - Balanced accuracy score of 54%
  - percision score of 99%
  - recall score of 40%
![image](https://user-images.githubusercontent.com/109539205/205723071-288ade00-6369-4b42-8576-bb192204cdd4.png)

Combination (SMOTEENN)
  - Balanced accuracy score of 64%
  - percision score of 99%
  - recall score of 57%
![image](https://user-images.githubusercontent.com/109539205/205723386-d80c7eff-d9df-4cd4-9d75-e86b4390bc93.png)

### Ensemble Learners

BalancedRandomForestClassifier
  - Balanced accuracy score of 78%
  - Percision score of 99%
  - recall score of 87%
![image](https://user-images.githubusercontent.com/109539205/205724834-5d9342f7-d771-4fee-a9ab-098edd038139.png)

EasyEnsembleClassifier
  - Balanced accuracy score of 93%
  - Percision score of 99%
  - Recall score of 94%
![image](https://user-images.githubusercontent.com/109539205/205725033-11e824f4-81bb-401f-b17e-9446893483e1.png)


## Summary 

In summary, if we were to use a model in the future for predicting whether loan applications will pass or fail, we would use the EasyEnsembleClassifier model. This was the most accurate and had the best recall percentage out of all the models. 
