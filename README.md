# credit-risk-classification
UCB Data Analysis Bootcamp Module 20 Supervised Machine Learning


## Installation

Software Jupyter Notebook is being used to write the code, and to generate the results, and the environment is PythonDataUCB, provided by UC Berkeley.


## Description

This is the Module 20 challenge for the UC Berkeley Data Analyticd Boot Camp. In this challenge, we are using different techniques to train and evaluate a model based on loan risk. The dataset is a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrows.

Two methods are used to build the model and make predictions: the Logistic Regression Model and the Logistic Regression Model with Resampled Training Data.

In the first method, Logistic Regression Model, it is better in predicting healthy loans than high-risk loans.

Accuracy score: 0.9442676901753825
For healthy loans: 
- Precision score: 1.00
- Recall score: 1.00

For high-risk loans:
- Precision score: 0.87
- Recall score: 0.89

As for the second method, Logistic Regression Model with Resampled Training Data, they have a similar result as the first method.

Accuracy score: 0.9959744975744975
For healthy loans: 
- Precision score: 1.00
- Recall score: 1.00

For high-risk loans:
- Precision score: 0.87
- Recall score: 1.00

By comparing the 2 methods, while both has similar accuracies and scores, the second method is recommended. The reason is the second method has a higher accuracy score, and recall score for high-risk loans.
