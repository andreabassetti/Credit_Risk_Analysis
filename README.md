# Credit_Risk_Analysis

## Purpose
The purpose of this challenge is to ass credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. I will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results
- Naive Random Oversampling: The balances accuracy test was 64%, the precision for the high_risk was 1% and the recall was 60%, and lastly the precision for the low_risk was 100% and the recall was 69%.
![Naive Random Overampling](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling.png)

- SMOTE Oversampling: The balances accuracy test was 64%, the precision for the high_risk was 1% and the recall was 60%, and lastly the precision for the low_risk was 100% and the recall was 69%.
![SMOTE Oversampling](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling.png)

- Undersampling: The balances accuracy test was 64%, the precision for the high_risk was 1% and the recall was 60%, and lastly the precision for the low_risk was 100% and the recall was 69%.
![Undersampling](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

- Combination (Over and Under) Sampling: The balances accuracy test was 64%, the precision for the high_risk was 1% and the recall was 60%, and lastly the precision for the low_risk was 100% and the recall was 69%.
![Combination (Over and Under) Sampling](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Combination%20(Over%20and%20Under)%20Sampling.png)

- Ensemble Learners: The balances accuracy test was 77%, the precision for the high_risk was 3% and the recall was 67%, and lastly the precision for the low_risk was 100% and the recall was 88%.
![Ensemble Learners](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Ensemble%20Learners.png)

- Easy Ensemble AdaBoost Classifier: The balances accuracy test was 92%, the precision for the high_risk was 9% and the recall was 89%, and lastly the precision for the low_risk was 100% and the recall was 94%.
![Easy Ensemble AdaBoost Classifier](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png)


## Summary
The Ensemble Learners and Easy Ensemble AdaBoost Classifier both showed a significantly higher accuracy and recall for high risk credit compared to Naive Random Sampling, SMOTE Oversampling, Undersampling and a combination of both. All of the models used in this challenge are showing low levels of precision for high risk  credit.  Because you want a good balance of precision and risk, i would chose the Ensemle Learners since it has a high accuracy and a more balance precision and recall score. 