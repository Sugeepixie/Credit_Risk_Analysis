# Credit_Risk_Analysis
## Overview of the Analysis
The purpose of this project is to build and evaluate following machine learning models to analyze credit risk
* Oversampling the data using RandomOverSampler and SMOTE models
* Undersampling the data using ClusterCentroid model
* Combination approch of Over and Undersampling using SMOTEENN model
* Ensemble learning by combining multiple models to improve accuracy using BalancedRandomForestClassifier and EasyEnsembleClassifier

## Results
### Naive Random Oversampling
The Balanced Accuracy Score is 65%, 
Image1

### SMOTE Oversampling
The Balanced accuracy score is 66.2%
Image1

### ClusterCentriod Undersampling
The Balanced accuracy score is 66.2%
Image1

### SMOTEENN Combination Sampling
The Balanced accuracy score is 55.2%
Image1


### Balanced Random Forest Classifier 
The Balanced accuracy score is 78.2%
Image1


### Easy Ensemble AdaBoost Classifier
The Balanced accuracy score is 90.2%
Image1


## Summary
In the first four models, the accuracy is not as high as the ensemble classifiers and the precision and fecall is low as well.Typically the modles should have a good balance of precision and recall. 
My recommendation is  the ensemble classifiers over the oversampling, undersampling, and combination models. The Easy Ensemble classifier has the best balance of all because of it's high accuracy score and good balance of precision and recall scores
