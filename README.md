Stock Price Prediction using LSTM


This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices based on historical time series data. The goal is to capture temporal patterns in stock price movements and generate future predictions.


Methodology

Data Preprocessing: Normalization of stock prices. Creation of sliding window sequences (sequence length = 30)

Model Training: LSTM layers used to capture temporal dependencies. Trained on historical price data

Evaluation: Model predictions compared against actual prices. Visualized predicted vs real values


Results: The model successfully learns general trends in stock prices with test RMSE 0.12648713462181738. Predictions follow the overall direction but may lag in sudden changes
