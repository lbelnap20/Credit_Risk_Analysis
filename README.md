# Credit_Risk_Analysis

## Overview 
This analysis uses 6 different machine learning models to predict credit risk. Because there are many more low-risk loan vs high-risk, the sample data is skewed and will cause inaccurate predictions. These machine learning models test different sampling techniques to compensate.
## Results
Presicion is the number of loans identified as high-risk that are truly high-risk. Larger numbers indicate a higher success rate of correctly identifying these loans, lower numbers indicate the models are incorrectly low-risk loans as high-risk. 

Recall (Sensitivity) is the percentage loans that are high-risk and are also correctly identified by the model. 

Accuracy is the number of loans correctly labeled as high or low-risk by the model. 

-Oversampling- 

  Precision: 1%. This model is incorrectly labeling the majority of actual low-risk loans as high-risk.
  
  Recall : 70%. This percentage is inflated due to the number of inccorectly labeled loans. 
  
  Accuracy Score: 64%
![oversampling](https://github.com/lbelnap20/Credit_Risk_Analysis/blob/main/Images/oversampling.jpg)

-Undersampling- 

  Precision: 1%. This model is incorrectly labeling the majority of actual low-risk loans as high-risk.
  
  Recall : 69%. This percentage is inflated due to the number of inccorectly labeled loans. 
  
  Accuracy Score: 64%
![undersampling](https://github.com/lbelnap20/Credit_Risk_Analysis/blob/main/Images/undersampling.jpg)

-SMOTE Oversampling-

  Precision: 1%. This model is incorrectly labeling the majority of actual low-risk loans as high-risk.
  
  Recall : 63%. This percentage is inflated due to the number of inccorectly labeled loans. 
  
  Accuracy Score: 66%
![smote](https://github.com/lbelnap20/Credit_Risk_Analysis/blob/main/Images/smoteOversampling.jpg)

-SMOTEEN-

  Precision: 1%. This model is incorrectly labeling the majority of actual low-risk loans as high-risk.
  
  Recall : 72%. This percentage is inflated due to the number of inccorectly labeled loans. 
  
  Accuracy Score: 65%
![smoteen](https://github.com/lbelnap20/Credit_Risk_Analysis/blob/main/Images/smoteen.jpg)

-Random Forest- 

  Precision: 59%. This model is incorrectly labeling a little less than half of actual low-risk loans as high-risk.
  
  Recall : 32%. This percentage is decreased due to the number of ccorectly labeled loans. 
  
  Accuracy Score: 66%
![randomForests](https://github.com/lbelnap20/Credit_Risk_Analysis/blob/main/Images/randomForests.jpg)

-Easy Ensemble- 

  Precision: 59%. This model is incorrectly labeling a little less than half of actual low-risk loans as high-risk.
  
  Recall : 32%. This percentage is decreased due to the number of ccorectly labeled loans.
  
  Accuracy Score: 66%
![ee](https://github.com/lbelnap20/Credit_Risk_Analysis/blob/main/Images/easyEnsembles.jpg)

## Summary 
Although the accuracy score across all models has little variation, only the Random Forest and Easy Ensemble model have higher precision and lower recall. These models are better overall at correctly identifying low-risk loans. The other models are more likely to label low-risk loans as high and deny the loans, decreasing consumers for the financial institution. I would recommend a larger dataset and further refining of these two models to increase accuracy.
