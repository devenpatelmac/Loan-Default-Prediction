# Loan Default Prediction

Problem Statement:
Using machine learning and deep learning models, can we predict if a given borrower is going to default on their loan payment?

Value Add:
Spotting customers with high financial uncertainty early on will help firms proactively manage their credit risk. Lenders will be able to determine what percentage of loans will be not be repaid, stopping that loan from being accepted in the first place.

Data Used:
LendingClub Accepted Loans 2007 - 2020

Process:
1. Clean Null Values
2. Remove redundant/bad columns
3. Downsample data to 60/40
4. Run Logistic Regression, KNN, and XGBoost models
5. Tune hyperparameters of the top performing model
5. Evaluate final model on test data
6. Conclude insights