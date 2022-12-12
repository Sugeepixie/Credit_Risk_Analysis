# Credit_Risk_Analysis
## Overview of the Analysis
The purpose of this project is to build and evaluate following machine learning models to analyze credit risk
* Oversampling the data using RandomOverSampler and SMOTE models
* Undersampling the data using ClusterCentroid model
* Combination approch of Over and Undersampling using SMOTEENN model
* Ensemble learning by combining multiple models to improve accuracy using BalancedRandomForestClassifier and EasyEnsembleClassifier

## Results
### Naive Random Oversampling

The Balanced accuracy score is **62%**

![RandomOverSampler](https://user-images.githubusercontent.com/76926148/206973020-b8d1d071-785e-4d23-9cb7-00d4f9d3144f.PNG)


### SMOTE Oversampling

The Balanced accuracy score is **65%**

![SMOTE](https://user-images.githubusercontent.com/76926148/206973997-70d695d8-d9ba-455d-8c52-6d1d74f41e08.PNG)


### ClusterCentriod Undersampling

The Balanced accuracy score is **51.6%**

![ClusterCentroid](https://user-images.githubusercontent.com/76926148/206974206-bf713397-ba92-42f1-8d3f-1ba310159cf1.PNG)


### SMOTEENN Combination Sampling

The Balanced accuracy score is **63.7%**

![SMOTEENN](https://user-images.githubusercontent.com/76926148/206974327-51963831-d99d-4f54-9c22-cd6400d95c99.PNG)


### Balanced Random Forest Classifier 

The Balanced accuracy score is **78.7%**

![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/76926148/206974520-b938cdbf-cf6c-4364-89ba-1ee455348763.PNG)



### Easy Ensemble AdaBoost Classifier

The Balanced accuracy score is **92.5%**

![EasyEnsembleClassifier](https://user-images.githubusercontent.com/76926148/206974614-47a93618-7d1b-4fc6-9042-aaaa1842a782.PNG)


## Summary
In the first four models, the accuracy is not as high as the ensemble classifiers and the precision and fecall is low as well.Typically the modles should have a good balance of precision and recall. 
My **recommendation** is  the ensemble classifiers over the oversampling, undersampling, and combination models. The **Easy Ensemble classifier has the best balance of all** because of it's high accuracy score and good balance of precision and recall scores.
