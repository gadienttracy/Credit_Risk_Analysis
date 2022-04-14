# Credit_Risk_Analysis
## Purpose
  The purpose of this analysis is to use various Resampling Models, SMOTEENN, and Ensemble Classifiers to predict credit risk.

## Results
### Random OverSampling
![randomoversampler](https://user-images.githubusercontent.com/91269696/163282715-72b43059-a1d4-4a3b-b03e-93716fae6739.PNG)

The balanced accuracy score is 66%
The precision for the high_risk group is .01 very low, the low_risk group has a precision of 1.00 meaning it is accurate all the time. 
The recall score is .71 for the high_risk group and .6 for the low risk group, average .60 which is fairly good


### SMOTE OverSampling
![SMOTE oversampling](https://user-images.githubusercontent.com/91269696/163282736-56720636-d941-4e79-9722-09ca769935c6.PNG)

Balanced accuracy is 54%
The precision average, and values for the high and low risk groups is the same as all the other over and under samplings: 0.99, .01, and 1.
The recall score is .69 for the high_risk group and .4 for the low risk group, average .4 


### Cluster Undersampling
  ![Clusterundersample](https://user-images.githubusercontent.com/91269696/163282761-579999a8-e3a3-42a7-bb46-eed4055052af.PNG)

The balanced accuracy score is 54%
The precision average, and values for the high and low risk groups is the same as all the other over and under samplings: 0.99, .01, and 1.
The recall score is .67 for the high_risk group and .42 for the low risk group, average .42 


### SMOTEENN Combination Sampling
![SMOTEENN](https://user-images.githubusercontent.com/91269696/163282993-5e0afdc8-dba2-49f7-8bad-89639c41f57d.PNG)

The balanced accuracy score is 54%
The precision average, and values for the high and low risk groups is the same as all the other over and under samplings: 0.99, .01, and 1.
The recall score is .69 for the high_risk group and .4 for the low risk group, average .4

### Balanced Random Forest Classifier
![ensembleclassifier](https://user-images.githubusercontent.com/91269696/163283049-695e7a42-4999-4b41-85e1-49b6e42ac3cf.PNG)

The balanced accuracy score is 77% 
The precision average, and values for the high and low risk groups is: 0.99, .03, and 1.
The recall score is .65 for the high_risk group and .88 for the low risk group, average .88

### Easy Ensemble Classifier
![easyensembleclassifier](https://user-images.githubusercontent.com/91269696/163283132-7e7660ec-2991-4a28-bb3f-00ac320e3f7f.PNG)

The balanced accuracy score is 93% which is the highest accuracy score of the tests.
The precision average, and values for the high and low risk groups is: 0.99, .09, and 1.
The recall score is .92 for the high_risk group and .94 for the low risk group, average .94

## Summary
  The ensemble classifier tests have the highest accuracy and recall scores, the Easy Ensemble Classifier is the best fit for this data.  However, the precision score is very low for the high risk group.  Meaning we are not able to easily identify high risk loan applicants.  I would not reccommend using any of these tests to identify high risk loan applicants.
