# Credit_Risk_Analysis

## Overview
In this project, we will utilize machine learning to predict credit risk. We will build and evaluate models to predict credit risk for Fastlending, a peer to peer lending services company. By using machine learning to predicgt credit risk, we can provide a more reliable loans experience. Machine learning can help to predict good candidates for loans, which in turn will lead to lower default rates. 

## Results

### Naive Random Sampling
<img width="731" alt="NaiveRandomSampling" src="https://user-images.githubusercontent.com/100978922/177893215-8ed23323-c254-4f25-b694-0504e47fd12a.png">

Balanced Accuracy: 0.6533977140416822

Precision: The precision is low for High-risk loans and is high for Low-risk loans

Recall: High/Low risk = .63/.67

### SMOTE Oversampling
<img width="736" alt="SMOTEOversampling" src="https://user-images.githubusercontent.com/100978922/177893225-77835c46-0027-4319-8c36-087d7cec933a.png">

Balanced Accuracy: 0.6512291961274883

Precision: The precision is low for High-risk loans and is high for Low-risk loans

Recall: High/Low risk = .64/.66

### Undersampling
<img width="732" alt="Undersampling" src="https://user-images.githubusercontent.com/100978922/177893227-8006965a-73d9-423c-9474-24c6fdde2eb5.png">

Balanced Accuracy: 0.5205611354855344

Precision: The precision is high for High-risk loans and is low for Low-risk loans

Recall: High/Low risk = .57/.47

### Combination Under-Over Sampling
<img width="726" alt="Combination" src="https://user-images.githubusercontent.com/100978922/177893240-480cdeef-9dc2-4937-a7ab-16def77e763f.png">

Balanced Accuracy: 0.6184576831808422

Precision: The precision is high for High-risk loans and is low for Low-risk loans

Recall: High/Low risk = .69/.55

### Balanced Random Forest Classifier
<img width="717" alt="BalancedRandomForest" src="https://user-images.githubusercontent.com/100978922/178163418-20286354-deeb-4836-816e-3bc3a8376515.png">

Balanced Accuracy: 0.7877672625306695

Precision: The precision is low for High-risk loans and is high for Low-risk loans

Recall: High/Low risk = .67/.91

### Easy Ensemble Classifier
<img width="713" alt="EasyEnsemble" src="https://user-images.githubusercontent.com/100978922/178163422-3a2ab161-0110-44c4-9244-2d5e9de031ae.png">

Balanced Accuracy: 0.925427358175101

Precision: The precision is low for High-risk loans and is high for Low-risk loans

Recall: High/Low risk = .91/.94

## Summary

When comparing the models based on balanced accuracy scores, the one closest to 1 is the Easy Ensemble Classifier at .93. The other models are all significantly lower, with the Random Forest Classifier being the second highest at only .79. The recall scores also need to be as close to 1 as possible, which still makes the Easy Ensemble model the most ideal option; the high risk recall is .91 and the low risk recall is .94. Therefore, the Easy Ensemble Model is the best machine learning model to choose for further credit card analysis.
