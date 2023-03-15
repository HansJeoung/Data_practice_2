# Data Source
Dacon
('https://dacon.io/competitions/official/235713/overview/description')

# Problem Definition
Predict the degree of credit card delinquency for users.

# Target Type
Multi Classification

# EDA Explanation
-Small group data.(20,000)

-The target data is unbalanced.

-There is data where only label data is different and everything is duplicated. 
In other words, it is estimated that many people only change their credit ratings.

# Model(Using Hyperparameter)
-RF, GB, XGB, LGB, CATBOOST

-For Hyperparameter model I choose XGB model using the optuna.

# Evaluation for the contest data
-Logloss(predict_proba)
