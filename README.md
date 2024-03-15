# Singapore-Resale-Flat-Prices-Predicting

## Problem Statement:
This project aims to develop and deploy a machine learning model that predicts the resale prices of flats in Singapore. The model will use historical data of resale flat transactions as the input, and output the estimated resale value of a flat. The model will be integrated into a user-friendly web application that can assist both potential buyers and sellers in making informed decisions about the resale market.

## Domain : Real Estate

## Prerequisites
1. **Python** -- Programming Language
2. **pandas** -- Python Library for Data Visualization
3. **numpy** --  Fundamental Python package for scientific computing in Python
4. **streamlit** -- Python framework to rapidly build and share beautiful machine learning and data science web apps
5. **scikit-learn** -- Machine Learning library for the Python programming language

## Data Source
**Link** : https://beta.data.gov.sg/collections/189/view

## Roadmap

- Get the data from the source - https://beta.data.gov.sg/collections/189/view.

- Cleaning the data and dealing with data types.

- Feature engineering to increase the accuracy of the model.
- Building and training the model.
- Creating the user friendly web page to get the features and show the predicted resale price.


## Explanation

- Firstly get the data from the source, which is a collection of datasets on the resale prices of flats in Singapore from 1990 to till date. The data can be downloaded from [this link](https://www.analyticsvidhya.com/blog/2021/04/steps-to-complete-a-machine-learning-project/).
- The process moves to cleaning the data and deal with data types. This involves checking for missing values, outliers, duplicates, and errors in the data. It also involves converting categorical variables into numerical ones, such as using one-hot encoding or label encoding. Additionally, it involves scaling or normalizing the numerical variables to have similar ranges and distributions.
- Then, performed feature engineering to increase the accuracy of the model. This involves creating new features from existing ones, such as using polynomial features, interaction terms, or domain knowledge. It also involves selecting the most relevant features for the model, such as using correlation analysis, feature importance, or dimensionality reduction techniques.
- After that, built and trained the model. This involves choosing a suitable machine learning algorithm for the regression problem, such as linear regression, decision tree, or random forest. Moreover, it involves evaluating the performance of the model, such as using cross-validation, mean squared error, or R-squared score.
- Lastly, created a user-friendly web page to get the features and show the predicted resale price. This involves using a web framework, such as streamlit, to create the front-end and back-end of the web application. It also involves creating a user interface, such as using streamlit components, to design the layout and style of the web page.

