Module 12 Report 

The purpose of this analysis was to develop a machine learning model to predict high-risk or healthy loans. We were given the loan size, interest rate, borrower’s income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The goal was to predict loan status: 0 for healthy and 1 for high-risk loans.

The first step was to split the data into two parts: one for training the model and one for testing it. I then imported LogisticRegression from sklearn to create the model. Next, I trained the model using the training dataset so that it could make predictions.

The results for Model 1 were:

Accuracy: 99%
Precision: 100% for healthy loans and 85% for high-risk loans
Recall: 99% for healthy loans and 91% for high-risk loans

In summary, the LogisticRegression model is very accurate. It is perfect for finding healthy loans and still highly accurate for identifying high-risk loans. I recommend this model for its high accuracy.