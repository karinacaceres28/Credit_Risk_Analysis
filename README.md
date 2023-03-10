# Credit_Risk_Analysis

## Overview
The purpose of this project was to predict credit risk by using Python to build and evaluate several machine learning models. While using the credit card credit dataset, oversampling the data was done using the RandomOverSampler and SMOTE algorithms, and undersampling using the ClusterCentroids algorithm. The over and undersampling combinational approach was done using the SMOTEEN algorithm. The two machine learning modules BalanceRandomForestClassifier and EasyEnsemnleClassifier were used to reduce bias and predict the credit risk.


## Results

### Native Random Oversampling
<img width="711" alt="NativeRandomOversampling 1" src="https://user-images.githubusercontent.com/110318652/213596213-4e889eb0-336f-4629-a085-b2f3f3ef9c1f.png">
    
    - Balance Accuracy Score: 0.6456130066757718
    - Precision Score: high_risk is 0.01, low_risk is 1.00, and the total is 0.99
    - Recall Score: high_risk is 0.61, low_risk is 0.68, and the total is 0.68

### SMOTE Oversampling
<img width="702" alt="SMOTE-Oversampling 2" src="https://user-images.githubusercontent.com/110318652/213597265-14ae46e0-793c-4ea8-8625-fc2ca19715ee.png">
    
    - Balance Accuracy Score: 0.6234433606890912
    - Precision Score: high_risk is 0.01, low_risk is 1.00, and the total is 0.99
    - Recall Score: high_risk is 0.70, low_risk is 0.58, and the total is 0.58

### Undersampling - ClusterCentroids
<img width="697" alt="ClusterCentroidsUndersamping 3" src="https://user-images.githubusercontent.com/110318652/213596231-fb3e8fd5-9ad0-4454-aabe-56e0e2349599.png">
    
    - Balance Accuracy Score: 0.6395687540036501
    - Precision Score: high_risk is 0.01, low_risk is 1.00, and the total is 0.99
    - Recall Score: high_risk is 0.61, low_risk is 0.64, and the total is 0.64

### Combination Sampling - SMOTEENN
<img width="704" alt="SMOTEEN- Combination Sampling 4" src="https://user-images.githubusercontent.com/110318652/213596245-82c33917-b091-4851-bfdc-151f2eb39b59.png">
    
    - Balance Accuracy Score: 0.6395687540036501
    - Precision Score: high_risk is 0.01, low_risk is 1.00, and the total is 0.99
    - Recall Score: high_risk is 0.70, low_risk is 0.58, and the total is 0.58
    
### Balance Random Forest Classifier
<img width="702" alt="BalancedRandomForestClassifier 5" src="https://user-images.githubusercontent.com/110318652/213596265-d1cc77d0-4e0a-47ff-8f70-b7fe84cdb76b.png">
     
    - Balance Accuracy Score:0.7877672625306695
    - Precision Score: high_risk is 0.04, low_risk is 1.00, and the total is 0.99
    - Recall Score: high_risk is 0.67, low_risk is 0.91, and the total is 0.91

### Easy Essemble Classifier
<img width="698" alt="EasyEnsembleClassifier 6" src="https://user-images.githubusercontent.com/110318652/213596306-528f8a0c-c5d7-440e-ac27-ef9ccf4376c5.png">
    
    - Balance Accuracy Score: 0.925427358175101
    - Precision Score: high_risk is 0.07, low_risk is 1.00, and the total is 0.99
    - Recall Score: high_risk is 0.91, low_risk is 0.94, and the total is 0.94
    
    
## Summary
The results indicate that the EasyEnsembleClassifier model had the best accuracy rate, yielding 92% accuracy. It also showed to yield 9% precision for the high-risk candidates. It was also shown to have the highest recall score, showing 91% for high_risk and 94% for low_risk. The remaining five models did not yield higher than 80% balance accuracy. The precision score was also shown to be similar for all models, high-risk ranging 0.01 ??? 0.07 and low-risk having 1.00 for each. The EasyEnsembleClassifier model has shown to be the better model for predicting the credit risk and any further credit card analysis.
