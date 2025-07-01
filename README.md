# Stock Price Analysis and Prediction using GBM and LSTM

This project implements a hybrid machine learning model that combines Gradient Boosting Machines (GBM) for feature selection with Long Short-Term Memory (LSTM) neural networks for time-series forecasting. The goal is to provide accurate and interpretable predictions of stock price trends by capturing both the importance of individual features and the sequential dependencies inherent in financial data.

Stock market data is complex, high-dimensional, and affected by numerous variables over time. Traditional models may struggle to capture these dynamics effectively. To address this, the project first applies GBM (such as XGBoost or LightGBM) to identify and rank the most influential features driving stock movements. These selected features are then used to train an LSTM model that learns temporal patterns in the stock prices and forecasts future values. The model output includes visual comparisons of predicted versus actual prices, along with feature importance charts and evaluation metrics like RMSE and MAE.

The entire project is developed in Python using libraries such as pandas and numpy for data preprocessing, matplotlib and seaborn for visualization, scikit-learn and xgboost or lightgbm for gradient boosting, and TensorFlow or Keras for implementing LSTM networks. Stock data can be imported from CSV files or directly fetched using tools like yfinance.

The pipeline includes steps for data cleaning, normalization, GBM-based feature selection, LSTM training, model evaluation, and visualization. It is particularly useful for short-term or mid-term stock price forecasting, creating informed algorithmic trading strategies, or serving as a research and learning tool in the domain of financial data science.

To get started, clone the repository and install the necessary dependencies listed in the requirements.txt file. Prepare your dataset in CSV format or configure the script to use yfinance. Running the main script or Jupyter notebook will guide you through preprocessing, model training, and generating predictions.

The repository is organized into folders for data storage, saved models, notebooks, utility functions, results, and a main script. This makes it easy to maintain and scale the project. The current implementation is modular and extensible, allowing for future enhancements such as integrating sentiment analysis from news or social media, adding technical indicators like MACD or RSI, expanding to multi-stock or portfolio-level prediction, or deploying the model as a web-based forecasting tool using frameworks like Streamlit or Flask.

This project was developed by Siddharth Panda. For more information or collaboration, feel free to visit the GitHub and LinkedIn profiles linked in the repository.
