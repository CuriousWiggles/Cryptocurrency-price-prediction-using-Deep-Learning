#Project Overview

# Cryptocurrency Price Prediction Using LSTM Models

This project implements Long Short-Term Memory (LSTM) neural networks to predict the closing prices of three cryptocurrencies: Bitcoin (BTC), Solana (SOL), and XRP. The models are built using Python and the TensorFlow/Keras library, leveraging historical data to forecast future prices.

---

# Files in the Repository:
1. `new_btc_codes.ipynb`:
   - Contains the LSTM model for predicting the closing prices of Bitcoin (BTC).
   - Includes data preprocessing, model training, and evaluation steps.

2. `sol_codes.ipynb`:
   - Implements an LSTM model for forecasting the closing prices of Solana (SOL).
   - Follows a similar approach to the Bitcoin model.

3. `xrp_codes.ipynb`:
   - Develops an LSTM model to predict XRP closing prices.
   - The process involves data cleaning, feature scaling, and model evaluation.

---

# Features

- Data Source: Historical OHLC (Open, High, Low, Close) data is fetched from reliable APIs or sources like Yahoo Finance.
- Preprocessing: The notebooks include steps for:
  - Data cleaning and handling missing values.
  - Feature scaling (e.g., MinMaxScaler) for better model performance.
- Model:
  - LSTM neural networks are used for time series forecasting.
  - Optimized hyperparameters such as learning rate, number of neurons, and epochs.
- Visualization: Plots of actual vs. predicted prices are provided to visualize model performance.

---

# How to Use

1. Clone this repository:
   bash git clone https://github.com/yourusername/cryptocurrency-price-prediction.git
