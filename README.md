# Stock-Price-Prediction
This notebook demonstrates how to build a stock price prediction model using a Multi-layer Perceptron (MLP) Regressor. The model utilizes historical closing prices to predict future prices.



# Overview
The notebook performs the following steps:

1. Install necessary libraries: Installs yfinance for fetching stock data.
2. Import libraries: Imports required libraries like pandas, numpy, scikit-learn, and matplotlib.
3. Load Data: Downloads historical stock data for a specified ticker (default is AAPL) using yfinance.
4. Feature Engineering: Creates lagged features (previous 7 days of closing prices) to use as input for the model.
5. Data Splitting: Splits the data into training and testing sets.
6. Data Scaling: Scales the features using StandardScaler.
7. Train Neural Network: Trains an MLPRegressor model on the training data.
8. Evaluate Performance: Evaluates the model's performance using RMSE and MSE.
9. Visualize Result: Plots the actual and predicted stock prices.
10. Prediction: Predicts the closing price for the next day.
