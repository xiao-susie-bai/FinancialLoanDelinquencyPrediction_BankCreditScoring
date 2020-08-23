# Bank Financial Loan Delinquency Prediction

Credit scoring mechanism is always of fundamental importance for banks in consumer lending, as poor credit algorithm may lead to huge loss. This project is mainly intended to build an optimal model for predicting whether a financial loan borrower would probably experience default or not in the next two years. Our goal is to help banks to improve the credit scoring mechanism and thus make better decisions on approval of granting a loan to a particular borrower.

The data is obtained from a 2011 Kaggle competition "Give Me Some Credit"(https://www.kaggle.com/c/GiveMeSomeCredit), with 11 variables in total (binary target variable). The training and testing datasets contain ~150,000 data entries.

In this data mining project, the data is preprocessed through several steps, including resampling (SMOTE oversampling & undersampling) of the originally highly unbalanced data (with regard to label) in particular. A multitude of predictive models for the classification task are used, such as logistic regression, KNN, Naïve Bayes, classification tree, neural network, random forest, gradient boosting, and adaptive boosting. The final optimal model chosen is adaptive boosting with best tuned parameters through model selection. We also draw insights (e.g. some most important features and models in the training process) and reflect on potential improvement for the future work in the end.

