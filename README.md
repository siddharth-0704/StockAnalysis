# Stock Price Analysis and Prediction using GBM and LSTM
This project implements a hybrid machine learning model that combines Gradient Boosting Machines (GBM) for feature selection with Long Short-Term Memory (LSTM) neural networks for time-series forecasting. The goal is to provide accurate and interpretable predictions of stock price trends by capturing both the importance of individual features and the sequential dependencies inherent in financial data.

# Overview
Stock market data is complex, high-dimensional, and affected by numerous variables over time. Traditional models may struggle to capture these dynamics effectively. This project addresses the challenge by:
  Using GBM (e.g., XGBoost or LightGBM) to identify and rank the most influential features in stock movement.
  Training an LSTM network on the selected features to learn temporal patterns and forecast future prices.
  Visualizing predictions and feature importance while evaluating model performance using standard metrics.

# Technologies Used
Programming Language: Python
Libraries and Tools: pandas, numpy for data preprocessing, matplotlib, seaborn for visualization, scikit-learn, xgboost or lightgbm for GBM-based feature selection
tensorflow or keras for LSTM implementation
yfinance (optional) for fetching real-world stock data

# Features
Data cleaning, normalization, and transformation
Feature ranking using GBM to reduce noise and dimensionality
Sequential modeling using LSTM for future stock price prediction
Visualization of actual vs predicted stock prices
Evaluation using RMSE, MAE, and other metrics for forecasting accuracy

# Use Cases
Predicting short-term or mid-term stock price trends
Enhancing algorithmic trading strategies through informed feature selection
Exploring financial data for research or educational purposes
Creating a base framework for deploying a real-time financial forecasting system
Getting Started
Clone the repository
Install dependencies from requirements.txt
Prepare or fetch stock data
Run the main script or notebook to preprocess data, train the GBM and LSTM models, and generate predictions
Evaluate results and visualize output

# Future Enhancements
Integrate news or sentiment analysis as additional features
Include technical indicators like MACD, RSI, Bollinger Bands
Expand to multi-stock prediction for portfolio-level forecasting
Deploy as an interactive web dashboard using Streamlit or Flask

# Author
Siddharth Panda
