# PAYGO CREDIT PAYMENT

This project cleans, processes and trains paygo credit repayment customer data and predicts payment for the next 6 months.

By Martin Mburu

Current Version: 01-09-2021


# DESCRIPTION

This project has two notebooks. Paygo.ipynb notebook has uploaded three datasets: metadata.csv, training.csv and testing.csv. 
This notebook cleans and processes data for training.  It produces two datasets, train_data.csv and test_data.csv
ModellingPaygo.ipynb notebook contains five models: linear regressor, k-nearest neighbour regressor, random forest regressor, neural network and catboost regressor. 
These models are trained on train_data.csv and predict on test_data.csv. The concept used is multi-output regression. 
It predicts credit payment for the next six months. I used the catboost regressor for deployment.
The results were evaluated. It has a root mean squared error of 684.91.  It ranked 13 out of 278 on SFC PAYGo Credit Repayment Competition on zindi.


# SETUP AND REQUIREMENTS

You must have a jupyter notebook and anaconda prompt

# TECHNOLOGY USED

Language: Python

Libraries: Pandas, Sklearn, Tensorflow, Keras

IDE: Jupyter notebook


SUPPORT AND CONTACT DETAILS

If you run to an issue or bug or you have a problem send me an email at mmburu961@gmail.com.

You are free to use, copy, modify or merge my code or change if there is an issue. Two heads are better than one.


LICENSE

Apache 2.0

Copyright (c) 2021

mmburu8
