# 📈 Stock Price Trend Prediction with LSTM
## 🎯 Objective
This project aims to predict future stock prices using a Long Short-Term Memory (LSTM) neural network. It enhances traditional forecasting by integrating key technical indicators like RSI, MACD, and Moving Averages.

## 📁 Dataset
File Name: HistoricalQuotes.csv
Source: Yahoo Finance or similar platforms
Includes: Historical stock data with fields like Date, Open, High, Low, Close, and Volume.

## ⚙️ Technologies & Libraries
Python (Jupyter Notebook)
Pandas, NumPy
Matplotlib, Seaborn
scikit-learn
TensorFlow / Keras
TA-Lib or ta for technical indicators

## 🧠 Features Used
Feature	Purpose
LSTM	Learns long-term patterns in time series data
RSI	Indicates overbought or oversold conditions
MACD	Captures trend reversals in momentum
Moving Averages	Smoothens price data for short and long terms
Data Scaling	Normalizes input for better neural network learning

## 🧪 Project Flow
Data Collection – Historical stock data loaded and cleaned
Feature Engineering – RSI, MACD, MA50, MA20 added
Preprocessing – Scaling, reshaping, and splitting
Model Training – LSTM neural network built and trained
Prediction – Future stock prices forecasted
Evaluation – Plots and performance metrics used to analyze accuracy

## 📊 Output
Visual comparison of real vs. predicted prices
Trend chart with technical indicators
Accuracy metrics like RMSE or MAPE

## 🔍 Future Enhancements
Real-time stock data integration
Deploy using a web interface (Flask or Streamlit)
Add sentiment analysis based on financial news
