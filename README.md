# Credit-Card-Fraud_Detection
Detecting the fradulent credit card transactions

# Problem Description

As we know, out of million transcation, 1000 transactions are being fradulent. So, when training a ML model to detect the fradulent credit card transactions, it is often difficult to find the dataset balanced. This is class imbalance and in the project, with the use of several ML algorithms, we tackle the problem of fradulent transactions. We foucs on model performance instead of model accuracy. 

# Dataset

The dataset used in this project have 492 fraudulent transactions out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for only 0.172% of all transactions. The dataset is available for download at https://www.kaggle.com/mlg-ulb/creditcardfraud

# Algorithms
1. Logisitc regression
2. Random Forest
3. XGBoost classifier

These alogrithms are trained on original dataset and on dataset after performing Synthetic Minority Over-Sampling Technique(SMOTE) on the original dataset. 

# Metrics
1. F1 Score.
2. Recall.
3. Precision.
4. Confusion Matrix
5. Average precision-recall score.
6. Average ROC_AUC score.

# Results
The Logistic Regression gives the best Recall score on the original dataset among the three algorithms. However, it lags the other two classifiers on all other metrics. XGBoost gives the best F1 score among the classifiers. Using the classifiers on the SMOTE dataset improves the Recall of the models at the cost of Precision and F1 Score.
