# Credit Card Fraud Detection
# Problem Statement
The problem statement chosen for this project is to predict credit card fraud transactions with the help of machine learning models.

In this project, we will analyse customer-level data. The dataset is taken from the Kaggle Website containing 12,96,675 transactions of both legitimate and fraud transactions from the duration 1st January 2019 to 30th June 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants.
# Project Pipeline
The project pipeline can be briefly summarized in the following four steps:

**Data Understanding:** Here, we need to load the data and understand the features present in it. This would help us choose the features that we will need for your final model.

**Exploratory data analytics (EDA):** Normally, in this step, we need to perform univariate and bivariate analyses of the data, followed by feature transformations, if necessary. 

**Train/Test Split:** Now we are familiar with the train/test split, which we can perform in order to check the performance of our models with unseen data. We need to choose an appropriate k value so that the minority class is correctly represented in the test folds.

**Model-Building:** This is the final step at which we can try different models and fine-tune their hyperparameters until we get the desired level of performance on the given dataset. We should try and see if we get a better model by the various sampling techniques.

**Model Evaluation:** We need to evaluate the models using appropriate evaluation metrics. Note that since the data is imbalanced it is is more important to identify which are fraudulent transactions accurately than the non-fraudulent. We need to choose an appropriate evaluation metric which reflects this business goal.
