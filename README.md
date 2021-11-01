# Credit_Risk_Analysis

## Overview:

This project uses python and machine learning libraries to evaluate models that work with a credit card dataset that was given. We use the following models in our evalutation:
* RandomOverSampler
* SMOTE
* ClusterCentroids
* SMOTEENN
* BalancedRandomForestClassifier
* EasyEnsembleClassifier

## Results:
### RandomOverSampler
![image](https://user-images.githubusercontent.com/85656361/139720759-61ae3621-024b-4536-8021-3d1f7323437b.png)
![image](https://user-images.githubusercontent.com/85656361/139721339-82f1c75b-f9b1-4b54-8032-4df147f46198.png)
* balanced accuracy score: 65%
* High risk score: Precision - 1%, Recall - 67%
* Low risk score: Precision - 100%, Recall - 64%

### SMOTE
![image](https://user-images.githubusercontent.com/85656361/139721519-96811656-fda8-49c0-8541-d936b75c79f0.png)
![image](https://user-images.githubusercontent.com/85656361/139721570-84ff65f7-b829-49c0-84c1-571a582aead1.png)
* balanced accuracy score: 51%
* High risk score: Precision - 1%, Recall - 59%
* Low risk score: Precision - 100%, Recall - 43%


### ClusterCentroids
![image](https://user-images.githubusercontent.com/85656361/139721863-dfa50978-6da9-4172-975f-6b097cd4f8fc.png)
![image](https://user-images.githubusercontent.com/85656361/139721954-d66c1328-9b52-4231-86aa-64a7d114dffc.png)
* balanced accuracy score: 63%
* High risk score: Precision - 1%, Recall - 61%
* Low risk score: Precision - 100%, Recall - 64%


### SMOTEENN
![image](https://user-images.githubusercontent.com/85656361/139722118-a596eba9-7eaf-47fe-b9ac-a16b9f96cfa0.png)
![image](https://user-images.githubusercontent.com/85656361/139722146-688c9e0c-d953-414f-af06-6a4073334d6f.png)
* balanced accuracy score: 62%
* High risk score: Precision - 1%, Recall - 71%
* Low risk score: Precision - 100%, Recall - 54%

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/85656361/139722300-10c56d72-8e41-4d93-814a-52609e108c7e.png)
![image](https://user-images.githubusercontent.com/85656361/139722373-a661a65f-73dd-4e28-8333-9aaa8c4245c7.png)
* balanced accuracy score: 79%
* High risk score: Precision - 4%, Recall - 67%
* Low risk score: Precision - 100%, Recall - 91%


### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/85656361/139722512-a84471b0-addf-4fc8-86e4-53c596d14375.png)
![image](https://user-images.githubusercontent.com/85656361/139722559-90736581-880d-4762-9bc2-b10b542a0532.png)
* balanced accuracy score: 92%
* High risk score: Precision - 7%, Recall - 91%
* Low risk score: Precision - 100%, Recall - 94%
* 
## Summary:

All of the models tested here had low precision when testing for high credit risk. The Easy Ensemble AdaBoost Classifier model has a balanced accuracy score of 92%, the best of all models. Even so, the best of the 6 still displays very low perentages of precision, therefore, I would not recommend any of these models to predict credit risk
