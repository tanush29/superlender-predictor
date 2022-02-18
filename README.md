# superlender-predictor

SuperLender is a local digital lending company. SuperLender wants to build machine learning model to lower the risk of loan default and deliver profitable and high-impact loan alternative. Now, try to predict if a loan was good or bad. This is binary classification business problem, where Good is 1 and Bad is 0.

Source : https://zindi.africa/competitions/data-science-nigeria-challenge-1-loan-default-prediction


Conclusion:

Our main objective is to make sure that we give loans to the right people while minimizing the loans to people who would not settle loan on time.

After cleaning and partitioning the data set, we use SMOTE to oversample the data since the data is unbalanced. Then, we standardize the z-score, and we perform RFE to find out the 10 most important features. We run the data through several machine learning tools to find out the best classifier. We used accuracy and AUC as our metrics, and we also looked at the confusion matrix to minimize the false positives. In the end, after performing grid search random forest performed the best, giving us an accuracy of 71% and AUC of 49%. We got 283 true positives on our test data, which outweighs the 96 false positives.

We believe this data is not very useful in predicting the loan defaulters due to the high numbers of false positives. Adding more data points or more correlated feature may help on improving the accuracy.
