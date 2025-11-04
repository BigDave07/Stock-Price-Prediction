# Stock-Price-Prediction
This notebook demonstrates how to build a stock price prediction model using a Multi-layer Perceptron (MLP) Regressor. The model utilizes historical closing prices to predict future prices.



# Overview
The notebook performs the following steps:

Install necessary libraries: Installs yfinance for fetching stock data.
Import libraries: Imports required libraries like pandas, numpy, scikit-learn, and matplotlib.
Load Data: Downloads historical stock data for a specified ticker (default is AAPL) using yfinance.
Feature Engineering: Creates lagged features (previous 7 days of closing prices) to use as input for the model.
Data Splitting: Splits the data into training and testing sets.
Data Scaling: Scales the features using StandardScaler.
Train Neural Network: Trains an MLPRegressor model on the training data.
Evaluate Performance: Evaluates the model's performance using RMSE and MSE.
Visualize Result: Plots the actual and predicted stock prices.
Prediction: Predicts the closing price for the next day.
