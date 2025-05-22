Stock Market Prediction Using LSTM with Explainable AI
Overview
This project implements a Long Short-Term Memory (LSTM) based deep learning model to predict stock prices of HDFC Bank using historical data. The model forecasts future stock prices by learning temporal patterns from past stock price trends. Additionally, explainable AI techniques, specifically SHAP (SHapley Additive exPlanations), are integrated to interpret the model’s predictions and provide insights into feature contributions.

Features
Historical stock data extraction using Yahoo Finance API (yfinance).

Data preprocessing and normalization with MinMaxScaler.

Stacked LSTM model architecture for time-series forecasting.

Model evaluation using metrics such as MAE, MSE, RMSE, and R² score.

Visualization of actual vs predicted stock prices and future forecasts.

Explainability of predictions using SHAP values and waterfall plots.
