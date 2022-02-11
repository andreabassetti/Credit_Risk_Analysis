# Credit_Risk_Analysis

## Purpose
The purpose of this challenge is to ass cfedit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. I will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results
- Naive Random Oversampling: The balances accuracy test was 64%, the precision for the high_risk was 1% and the recall was 60%, and lastly the precision for the low_risk was 100% and the recall was 69%.
![Naive Random Overampling](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling.png)

- SMOTE Oversampling: The balances accuracy test was 64%, the precision for the high_risk was 1% and the recall was 60%, and lastly the precision for the low_risk was 100% and the recall was 69%.
![SMOTE Oversampling](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling.png)

- Undersampling: The balances accuracy test was 64%, the precision for the high_risk was 1% and the recall was 60%, and lastly the precision for the low_risk was 100% and the recall was 69%.
![Undersampling](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)
![Combination (Over and Under) Sampling](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Combination%20(Over%20and%20Under)%20Sampling.png)
![Ensemble Learners](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Ensemble%20Learners.png)
![Easy Ensemble AdaBoost Classifier](https://github.com/andreabassetti/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png)







Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
