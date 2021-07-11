# Credit_Risk_Analysis

## Overview
Analysis of risk associated with loans based on other relevant financial data in a large dataset of borrowers.

## Results
* Oversampling, Undersampling, and SMOTEEN derived scores with an unreliable accuracy rate. Smoteen was the highest with 64% accuracy
[SMOTEEN results](https://github.com/qklm/Credit_Risk_Analysis/blob/main/SMOTEEN.png)
* RandomForestClassifier & EasyEnsembleClassifier derived a painfully accurate score based on training data
[RandomForestClassifier results](https://github.com/qklm/Credit_Risk_Analysis/blob/main/rfc.png)
[EasyEnsembleClassifier results](https://github.com/qklm/Credit_Risk_Analysis/blob/main/eec.png)

## Summary
Using any one model for something as important as loan granting (or anything generally involving money) is a poor choice. But a combination of EEC and RFC looks to be an effective way to get an incredibly accurate estimation for what loans will be paid, and which loans will not be. 
