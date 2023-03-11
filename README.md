# Credit_Risk_Analysis

## Overview
We are wroking on creating a model to classify individuals' credit risk into either high-risk or low-risk. We are comparing 6 different models to determine which serves our purposes best.


## Results

### Naive Random Oversampling Model:
- Balanced Accuracy Score: 84.2%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/RandomOversampler_BAS.png)

- High-Risk Precision: 2%
- High-Risk Recall: 84%
- Low-Risk Precision: 100%
- Low-Risk Recall: 85%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/RandomOversampler_ICR.png)

### SMOTE Oversampling Model:
- Balanced Accuracy Score: 85.8%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/SMOTE_BAS.png)

- High-Risk Precision: 3%
- High-Risk Recall: 85%
- Low-Risk Precision: 1%
- Low-Risk Recall: 87%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/SMOTE_ICR.png)

### Clustered Centroids Undersampling Model:
- Balanced Accuracy Score: 81.7%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/ClusterCentroids_BAS.png)

- High-Risk Precision: 2%
- High-Risk Recall: 87%
- Low-Risk Precision: 100%
- Low-Risk Recall: 76%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/ClusterCentroids_ICR.png)

### SMOTEENN Over/Undersampling Model:
- Balanced Accuracy Score: 85.5%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/SMOTEENN_BAS.png)

- High-Risk Precision: 3%
- High-Risk Recall: 85%
- Low-Risk Precision: 100%
- Low-Risk Recall: 86%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/SMOTEENN_ICR.png)

### Balanced Random Forest Classifier:
- Balanced Accuracy Score: 79.0%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/BalancedRandomForest_BAS.png)

- High-Risk Precision: 4%
- High-Risk Recall: 68%
- Low-Risk Precision: 100%
- Low-Risk Recall: 90%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/BalancedRandomForest_ICR.png)

### Easy Ensemble Classifier:
- Balanced Accuracy Score: 91.8%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/EasyEnsemble_BAS.png)

- High-Risk Precision: 7%
- High-Risk Recall: 90%
- Low-Risk Precision: 100%
- Low-Risk Recall: 94%
![](https://github.com/mzabrisk/Credit_Risk_Analysis/blob/a26cbe165511cef94961ffd37173b3039fad2b90/images/EasyEnsemble_ICR.png)


## Summary
  
