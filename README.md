# Challenge-17

## Project Purpose
The purpose of this project is to use a variety of machine learning methods in order to assess the credit risk of potential credit card holders and determine which method is the most effective.

## Results

- Naive Random Oversampling:

![This is an image](https://github.com/sandmanN7/Challenge-17/blob/main/Images/OS.png)

Balanced Accuracy: 62.5% Recall (High-Risk): 60% Precision (High-Risk): 1%

- Undersampling (ClusterCentroids):

![This is an image](https://github.com/sandmanN7/Challenge-17/blob/main/Images/US.png)

Balanced Accuracy: 52.9%  Recall: 61%  Precision: 1%

- SMOTE Oversampling:

![This is an image](https://github.com/sandmanN7/Challenge-17/blob/main/Images/SMOTE.png)

Balanced Accuracy: 65.1%  Recall: 64%  Precision: 1%

- Combination Over and Under Sampling (SMOTEENN):

![This is an image](https://github.com/sandmanN7/Challenge-17/blob/main/Images/COMBO.png)

Balanced Accuracy: 65%  Recall: 72%  Precision: 1%

- Balanced Random Forest Classifier:

![This is an image](https://github.com/sandmanN7/Challenge-17/blob/main/Images/rdm.png)

Balanced Accuracy: 78.8%  Recall: 67%  Precision: 3%


- Easy Ensemble AdaBoost Classifier: 

![This is an image](https://github.com/sandmanN7/Challenge-17/blob/main/Images/Ada.png)

Balanced Accuracy: 92.5%   Recall: 91%    Precision: 7%






## Summary

The best of the tried methods in this particular project would be the Easy Ensemble AdaBoost Classifier. It has the highest balanced accuracy, recall and preciscion percentages, in both evaluating high-risk and low-individuals. There are some interesting variations between the methods in that some are better at detecting high-risk individuals while some are better at finding those who are low-risk, though the Easy Ensemble AdaBoost Classifier appears the best overall by far.
