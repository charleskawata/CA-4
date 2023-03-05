# Data Cleaning and Transformation for Machine Learning
This code contains data cleaning and transformation steps to prepare data for machine learning models. The code also finds the optimal values for Accuracy Vs. n_estimators and AUC Vs. n_estimators, builds a random forest model, builds AdaBoost, Gradient Boost, and XGB, and then compares their performance.

## Prerequisites
This code requires Python 3.x and the following packages:

pandas
numpy
scikit-learn
matplotlib
seaborn
xgboost
You can install these packages using pip. For example:

## Copy code
pip install pandas numpy scikit-learn matplotlib seaborn xgboost

# The code generates the following results:

A plot of Accuracy Vs. n_estimators for the random forest model
A plot of AUC Vs. n_estimators for the random forest model
The optimal value of n_estimators for the random forest model
The optimal value of n_estimators for the AdaBoost model
The optimal value of n_estimators for the Gradient Boost model
The optimal value of n_estimators for the XGB model
A comparison of the performance of the random forest, AdaBoost, Gradient Boost, and XGB models in terms of Accuracy and AUC.
