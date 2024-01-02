# Model-Probability-of-Default-using Python

This notebook explores a data set to model Probability of Default(PD). PD is the likelihood that a borrower will fail to pay a certain debt. 

First, the data set is cleaned and prepared for modelling. Then, two classification models are applied; Logistic regression model and XGBoost model. Using the in-build feature extraction methods most significant features are identified for both models by tracking the training error of the model. The optimal models that gives the best training error is obtained. The two models are then evaluated and compared using metrics like precision, recall, and log loss.
