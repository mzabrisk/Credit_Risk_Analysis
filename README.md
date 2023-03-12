# Credit_Risk_Analysis

## Overview
We are wroking on creating a model to classify individuals' credit risk into either high-risk or low-risk. We are comparing 6 different models to determine which serves our purposes best: The Naive Random Oversampling Model, The SMOTE Oversampling Model, The Clustered Centroids Undersampling Model, The SMOTEENN Over/Undersampling Model, The Balanced Random Forest Classifier, and The Easy Ensemble Classifier. The models will be evaluated by examining the Balanced Accuracy Score, Precision (for classifying both high and low-risk), and recall (for classifying both high and low risk).


## Results

### Naive Random Oversampling Model:
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/RandomOversampler_BAS.png)


- Balanced Accuracy Score: 84.2%



![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/RandomOversampler_ICR.png)



- High-Risk Precision: 2%
- High-Risk Recall: 84%
- Low-Risk Precision: 100%
- Low-Risk Recall: 85%




### SMOTE Oversampling Model:
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/SMOTE_BAS.png)


- Balanced Accuracy Score: 85.8%



![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/SMOTE_ICR.png)


- High-Risk Precision: 3%
- High-Risk Recall: 85%
- Low-Risk Precision: 100%
- Low-Risk Recall: 87%




### Clustered Centroids Undersampling Model:
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/ClusterCentroids_BAS.png)


- Balanced Accuracy Score: 81.7%

![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/ClusterCentroids_ICR.png)


- High-Risk Precision: 2%
- High-Risk Recall: 87%
- Low-Risk Precision: 100%
- Low-Risk Recall: 76%


### SMOTEENN Over/Undersampling Model:
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/SMOTEENN_BAS.png)


- Balanced Accuracy Score: 85.5%



![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/SMOTEENN_ICR.png)


- High-Risk Precision: 3%
- High-Risk Recall: 85%
- Low-Risk Precision: 100%
- Low-Risk Recall: 86%




### Balanced Random Forest Classifier:
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/BalancedRandomForest_BAS.png)


- Balanced Accuracy Score: 79.0%





![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/BalancedRandomForest_ICR.png)


- High-Risk Precision: 4%
- High-Risk Recall: 68%
- Low-Risk Precision: 100%
- Low-Risk Recall: 90%




### Easy Ensemble Classifier:
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/EasyEnsemble_BAS.png)


- Balanced Accuracy Score: 91.8%



![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/EasyEnsemble_ICR.png)


- High-Risk Precision: 7%
- High-Risk Recall: 90%
- Low-Risk Precision: 100%
- Low-Risk Recall: 94%





## Summary
For the models we tested:
- The balanced accuracy score ranged from 79.0% to 91.8%
- The high-risk precesion ranged from 2% to 7%
- The high-risk recall ranged from 68% to 90%
- The low-risk precision was 100% for all models
- The low-risk recall ranged from 76% to 94%


The most important aspect of this model is to have a high recall for the high-risk population. It's ok for the model to misclassify some low risk individuals as high risk, but it needs to correctly categorize as many of the high-risk individuals as possible. With this in mind, the Easy Ensemble Classifier provides us with the best model for classifying credit risk. Not only did it have the highest recall for categorizing high-risk at 90%, but it also scored the best in all other metrics evaluated.
  
