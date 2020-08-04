# Credit-Case-Study-with-Python

## About
This project is an exploration of data science using Python, pandas, and sciki-learn.  It is based on the book "Data Science Projects with Python", by Stephen Klosterman, April 2019, Packt Publishing.  

A case study scenerio involving a hypothetical credit card company client is used.  The client has brought a dataset that includes some domographics and recent financial data (the past 6 months) for a sample of 30,000 account holders. This data is at the credit account level; in other words, there is one row for each account. Rows are labeled by whether in the next month after the 6 month historical data period, and account owner has defaulted - failed to make minimum payment.

The overall goal is to develop a predictive model for whether an account will default next month, given demographics and historical data.

The original dataset is a modified version from the University of California, Irvine Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
obtained from: http://archive.ics.uci.edu/ml
The modified data set used in this project can be found at: http://bit.ly/2Hlk5t3

## Sections

# Data Exploration and Cleaning

This section covers loading the csv data into Pandas dataframes.  Cleaning null and duplicate values.  Examining statistical summaries of the data.  Applying boolean masks and one-hot-encoding to transform columns of catagorical variables.  Creating histograms for feature visualization, and to aid in investigation of flaws in data.  

### Pertinent questions to ask in exploration.
How many columns, rows in data?
What kind of features are there? (numerical, categorical, boolean)
What does the data look like in these features?
i.e. range of numeric features, frequency of classes for categorical variables
Are there any missing values?


# Applying Scikit-Learn and Model Evaluation
This section shows how to split data to training and testing sets for use in logistic regression.  Accuracy, true and false positive and negative rates are summarized in a confusion matrix.  The regression model is used to predict probabilities, and precision-recall curves are introduced.
