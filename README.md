# Credit_Risk_Analysis

# Overview of the analysis

This work is focused on determining which supervised machine learning model is better when predicting credit risk.Several techniques were used with the machine learning models as it was Naive Random Oversampling, SMOTE Oversampling, Undersampling, Combination (Over and Under) Sampling, Balanced Random Forest Classifier, asy Ensemble AdaBoost Classifier. The results that will be evaluated to know which model with which technique was the one that gave the best result when predicting credit risk will be: Balanced Accuracy Scores, Precision and Recall


# Results

## Oversampling

### Naive Random Oversampling
Accuracy Scores: 64.9%  
Precision HR/LR: 1% / 100%  
Recall HR/ LR:   73% /57%   
![image](https://user-images.githubusercontent.com/66183125/151721038-a742f712-41ee-479a-8c6c-9bf6428cfe59.png)


### SMOTE Oversampling
Accuracy Scores:  65.84%   
Precision HR/LR: 1% / 100%  
Recall HR/ LR:   63% /68%

![image](https://user-images.githubusercontent.com/66183125/151721026-acac1596-4b85-4230-b1a2-d58db7f657e4.png)



## Undersampling
Accuracy Scores:  65.84%   
Precision HR/LR: 1% / 100%     
Recall HR/ LR:   63% / 68% 

![image](https://user-images.githubusercontent.com/66183125/151723094-88ec47ad-9d9d-425a-b5d5-8e514b3defa2.png)


## Combination (Over and Under) Sampling    ---SMOTEENN---
Accuracy Scores:      
Precision HR/LR: 1% / 100%       
Recall HR/ LR:   72%/57%
![image](https://user-images.githubusercontent.com/66183125/151720959-594491c7-4fad-46c7-bda9-47b319ebbf85.png)



## Ensemble Learners

### Balanced Random Forest Classifier
Accuracy Scores:   80.7%   
Precision HR/LR: 3% / 100%      
Recall HR/ LR:   72%/ 89%
![image](https://user-images.githubusercontent.com/66183125/151720945-c9e5d8db-74bb-45fc-85a4-988b7f115693.png)


### Easy Ensemble AdaBoost Classifier
Accuracy Scores: 90.7%   
Precision HR/LR: 7% / 100%      
Recall HR/ LR:   87% / 95%
![image](https://user-images.githubusercontent.com/66183125/151720938-7dfca143-d683-4dd1-ba7c-e327f6ae7c5e.png)


# Summary

Being able to be precise in terms of predicting a high level of credit risk seems quite difficult in any model but if we talk about sensitivity or recall we can see that each model performs differently. In the same way  if we evaluate the balanced_accuracy_score  we can see how our models will  perform with new information and  also we can know how good they will  predict the level of risk, they can do it better or worse depending on what we choose.Simply if I had to give a recommendation to choose one of these models, it would undoubtedly be EasyEnsembleClassifier, since it was able to correctly predict 90.7% of the data, it was also the one with the best Precision and Recall of all the models, both for credit risk high as low credit risk










