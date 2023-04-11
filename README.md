# Loan Default Prediction

Problem Statement:
Using machine learning and deep learning models, can we predict if a given loan applicant is going to default on their loan payment?

Value Add:
Spotting customers with high financial uncertainty early on will help firms proactively manage their credit risk. Lenders will be able to determine what percentage of loans will be not be repaid, stopping that loan from being accepted in the first place.

Data Used:
LendingClub Accepted Loans 2007 - 2020

Notebook 1: EDA and Cleaning
- Initial EDA
- Dropping columns with high NULL values
- EDA on redundant features
- EDA on features consisting of data after the issue date of the loan
- Cleaning remaining NULL values

Notebook 2: Processing 
- Converting categorical features into numerical features
- Dropping any features that don't make sense to convert
- Removing features that have a correlation above 70%

Notebook 3: Modeling
- Logistic Regression with and with out PCA
- Down sample data to 60% paid loans and 40% default loans
- Logistic Regression with and with out PCA
- Random Forest: base model, hyperparameter optimization and feature importance
- XGBoost: base model, hyperparameter optimization and feature importance

Best Model Results:

Best Model: XGBoost Classifier
Parameters: (booster='dart', n_estimators=200, max_depth=7, subsample=0.7, learning_rate=0.1)
Results:
- Default Recall: 91%
- Default Precision: 88%
- Paid Recall: 92%
- Paid Precision: 94%
- Overall Accuracy: 91%

End of File