# Project: Fraud Detection

## Problem Formulation
Due to the private nature of financial data, there is a lack of publicly available datasets that can be used for analysis. In this project, a synthetic dataset, publicly available on Kaggle, generated using a simulator called PaySim is used. The dataset was generated using aggregated metrics from the private dataset of a multinational mobile financial services company.

There are 6362620 instances of data set, The data set has 11 attributes which include is

Type of transactions
* Amount transacted
* Customer ID and Recipient ID
* Old and New balance of Customer and Recipient
* Time step of the transaction
* Whether the transaction was fraudulent or not

## Problem Statement
Leverage the given data set to build an End-to-End Data Science Project and find whether a transaction is Fradulent or not.

## Hypothesis Generation
This is one of the important stages in any Data Science/Machine Learning pipeline. It involves understanding the problem in detail by brainstorming as many factors as possible which can impact the outcome. It is done by understanding the problem statement thoroughly and before looking at the data.

Below are some of the factors which I think can highly affect the target i.e. Fraudulent transaction:

Type of transaction: Based on the type (mode) of payment might impact the fradulent transaction.

Amount: The amount of transaction can decide the transaction is fradulent or not, we can find unusual activities through the amount of transaction.

Initial Balance and Balance left: By comparing account balances before the transcation and after transaction we might able to find whether there is unusual activity is happened or not

## Steps to follow
It is a Binary Classification Problem

General Overview: Have a General Overview of the data
* ##### EDA: Perform Exploratory Data Analysis(EDA) to gain more clear insights of the data
* ##### Data Preprocessing: With the information gained after performing EDA, Preprocess the Data accordingly
* ##### Model Building: Once the data is properly cleaned and preprocessed, use this data to build a Machine Learning
* ##### Hyperparameter Tuning: Tune the Hyperparameters of the best performing model
* ##### Model Performance: Assess the Performance of the Model on the Testing data set
* ##### Save the model: Save the Best Performing Model
* ##### Predictions: Make Predictions on the Testing data set
