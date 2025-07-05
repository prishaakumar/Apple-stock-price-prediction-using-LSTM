# 📈 Apple Stock Price Prediction using LSTM

This project demonstrates how to use **Long Short-Term Memory (LSTM)** neural networks to predict the future closing prices of Apple Inc. ($AAPL) stock. It involves data preprocessing, visualization, model training, and evaluation—all implemented using Python and deep learning libraries.

---

## 🚀 Project Overview

📉 Stock price prediction is a classic problem in financial machine learning.  
In this project, we use **LSTM**, a type of recurrent neural network (RNN), to model and predict Apple stock closing prices based on historical data.

---

## ✅ Features

- 📊 Visualize and preprocess historical stock data
- 🔁 Use LSTM neural networks for time series forecasting
- 🧠 Train, test, and validate deep learning models
- 📉 Compare actual vs. predicted stock prices
- 💾 Save and load trained models

---

## 🛠️ Tech Stack

- **Python 3.x**
- **NumPy**, **Pandas** – data manipulation
- **Matplotlib**, **Seaborn** – data visualization
- **TensorFlow / Keras** – deep learning (LSTM implementation)
- **scikit-learn** – data preprocessing (MinMaxScaler)

---

## 📁 Folder Structure

Apple-stock-price-prediction-using-LSTM/
├── apple_stock_lstm.ipynb # Jupyter notebook with full code
├── AAPL.csv # Historical Apple stock data
├── model.h5 # Trained LSTM model (optional)
├── README.md # Project documentation
└── requirements.txt # List of Python dependencies



---

## 📉 Dataset

- Source: [Yahoo Finance](https://finance.yahoo.com/quote/AAPL/history)
- Ticker: `AAPL`
- Fields used: Date, Open, High, Low, Close, Volume

You can update `AAPL.csv` manually or automate it using `yfinance`.

---

## 🔍 Model Overview

- **Windowing:** The dataset is split into sequences of 60 time steps to predict the next day's closing price.
- **Architecture:** A simple stacked LSTM model with 2 layers and a Dense output layer.
- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Adam

---

## 📈 Visualizations

- Historical closing price trends
- Prediction vs. actual closing price
- Loss curve during training



---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/prishaakumar/Apple-stock-price-prediction-using-LSTM.git
cd Apple-stock-price-prediction-using-LSTM



