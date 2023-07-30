# credit-risk-classification
UCB Data Analysis Bootcamp Module 20 Supervised Machine Learning


## Installation

Software Jupyter Notebook is being used to write the code, and to generate the results, and the environment is PythonDataUCB, provided by UC Berkeley.


## Overview of the Analysis

This is the Module 20 challenge for the UC Berkeley Data Analyticd Boot Camp.

In this challenge, we are using different techniques to train and evaluate a model based on loan risk. The dataset is a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrows.

Procedures:
- Read the given CSV onto Jupyter Notebook
- Separate the CSV into the labels set (loan_status column) and the features set (the remaining columns)
- Split the data into training and testing dataset
- Fit the data into the models and make predictions
- Evaluate the model's performance

## Results

Two models are built and used to make predictions: the Logistic Regression Model (model 1) and the Logistic Regression Model with Resampled Training Data (model 2).

In the first model, Logistic Regression Model, it is better in predicting healthy loans than high-risk loans.

Accuracy score: 0.9442676901753825
For healthy loans: 
- Precision score: 1.00
- Recall score: 1.00

For high-risk loans:
- Precision score: 0.87
- Recall score: 0.89

As for the second model, Logistic Regression Model with Resampled Training Data, they have a similar result as the first method.

Accuracy score: 0.9959744975744975
For healthy loans: 
- Precision score: 1.00
- Recall score: 1.00

For high-risk loans:
- Precision score: 0.87
- Recall score: 1.00

## Summary

By comparing the 2 models, while both has similar accuracies and scores, the second model is recommended. The reason is the second model has a higher accuracy score, and recall score for high-risk loans. Although accuracy for both healthy and high-risk loans are important, the accuracy for high-risk loan is more important because as a company, making sure that they can collect the debt is crucial to running the business. Predicting accurately if the loan is a high-risk loan can help the business in lowering the chance of taking in high-risk loans, and prevent potential losses.
