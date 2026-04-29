# 📈 Stock Price Prediction using LSTM

## 📌 Overview
This project implements a **Long Short-Term Memory (LSTM)** neural network to predict stock prices based on historical time series data.

The goal is to capture temporal patterns in stock price movements and generate future predictions.

---

## 🧠 Model
- Model type: LSTM (Recurrent Neural Network)
- Framework: PyTorch / TensorFlow (update this based on your code)
- Input: Historical stock prices (sliding window approach)
- Sequence length: 30 time steps

---

## ⚙️ Methodology

1. **Data Preprocessing**
   - Normalization of stock prices
   - Creation of sliding window sequences (sequence length = 30)

2. **Model Training**
   - LSTM layers used to capture temporal dependencies
   - Trained on historical price data

3. **Evaluation**
   - Model predictions compared against actual prices
   - Visualized predicted vs real values

---

## 📊 Results

- The model successfully learns general trends in stock prices
- Predictions follow the overall direction but may lag in sudden changes

(*Optional: add RMSE if you have it*)

---
