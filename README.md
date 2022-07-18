# creditcardFraud
<img width="659" alt="Screenshot 2022-07-18 at 02 17 21" src="https://user-images.githubusercontent.com/100385953/179430655-654f9932-d2d3-4d85-925e-3d6130b3b41a.png">


In this project we will be first making our redictions using Machine Learning Techniques then we will be using Auto ML Technique to do the same. We will be using PyCaret in this notebook
Context

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase
In this project we will be implementing Anamoly detection to detect wheteher there is any fraudulent transaction.
Content

The dataset contains transactions made by credit cards in September 2013 by European cardholders.

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.
In this notebook we will perform the following task:

Data Analysis
Feature Engineering
Model Building and Prediction using ML Techniques
Model Building and Prediction using PyCaret(Auto ML)

<img width="940" alt="Screenshot 2022-07-18 at 02 19 25" src="https://user-images.githubusercontent.com/100385953/179430727-521938a2-acbb-4be0-816b-76f0d8f62451.png">

Solving the Problem Statement using PyCaret Library(Auto ML)
PyCaret : https://pycaret.org

PyCaret is an open source, low-code machine learning library in Python that allows you to go from preparing your data to deploying your model within minutes in your choice of notebook environment.
Installing Pycaret

!pip install pycaret
<img width="701" alt="Screenshot 2022-07-18 at 02 20 42" src="https://user-images.githubusercontent.com/100385953/179430761-5940f8da-be67-4839-a56b-ac6efae138ff.png">

