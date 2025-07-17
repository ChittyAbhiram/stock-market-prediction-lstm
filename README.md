# stock-market-prediction-lstm


# 📈 Stock Market Prediction using Stacked LSTM

This project uses a **Stacked LSTM (Long Short-Term Memory)** neural network to forecast stock prices based on historical data. LSTM networks are well-suited for time series problems like stock market prediction due to their ability to learn long-term dependencies.

## 📊 Dataset
- **Source**: [Tata Global stock price data](https://raw.githubusercontent.com/mwitiderrick/stockprice/master/NSE-TATAGLOBAL.csv)
- Daily historical stock data from the National Stock Exchange (NSE)

## 🔧 Project Pipeline

1. Load and preprocess stock price data
2. Normalize data using MinMaxScaler
3. Structure the data for LSTM input
4. Train a stacked LSTM model
5. Predict and visualize closing prices

## 🧠 Model Architecture

- LSTM (50 units, return_sequences=True)
- LSTM (50 units)
- Dense (1 unit)
- Optimizer: Adam
- Loss: Mean Squared Error

## 📈 Results

The model was trained on historical prices and successfully learned to forecast the closing price of Tata Global stock.




