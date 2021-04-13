This directory contain all code that was used for this Project.


The folder Notebooks contains all of the Jupyter Notebooks used in the project.

Introduction

This data is taken using yahoo finance (yfinance) for NSE stock index. The project idea is to check if it is possible to predict stock directional movement. In simple words, is stock is going up or down. Stock prices are highly volatile non-stationary, and challenging to predict. The objective is to be having better accuracy than 50%. 

I have taken basic data from yfinance, which is the date and close price. Since stock prices have some auto-regressive structure, we need to benefit from the same. More importantly, based on closed prices, we can have many indicators of different types that can help to create new features to predict stock prices better. Basic data taken from yfinance is enriched and then the Linear regression model is used to predict stock prices. 

The links to the project proposal and the write-up of the final project are below.

Included in this repository
1. Base Data Extract and Feature Generation - Download base data and enrich with new features - Execution order - Step 1
2. Feature Engineering - Select features based on co-relation and log co-relation - Execution order - Step 2
3. Train_Model_Base - Train the model with Dummy classifier - Base line the results - Execution order - Step 3
4. Train_Model_Final - Train the model with Logistic Regression - Base line the results - - Execution order - Step 4
5. Raw - Base data for NSE downloaded 
6. train.csv - Training data set
7. test.csv - Testing data set
8. Proposal.pdf - Proposal for the project
9. Report.pdf - Project report
10. README.md - This file.

This project is developed in Python 3.6.
You will need install some libraries in addition to standard ones inorder to run the code.
Libraries and respective version are:
1. yfinance 0.1.55





