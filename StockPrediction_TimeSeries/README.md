

Netflix Stock Price Analysis and Prediction using LSTM for Time Series Forecasting:

Overview
This project aims to analyze and predict Netflix's stock prices using historical data. It fetches the data from Yahoo Finance via the yfinance API and processes it for analysis and visualization. The project uses machine learning to predict future stock prices based on historical trends.

Features
Data Collection: Historical stock prices (Open, High, Low, Close) of Netflix are fetched using yfinance over a 5000-day period.
Visualization: A candlestick chart is generated using plotly to visualize stock price fluctuations over time.
Correlation Analysis: Correlation between stock price features like Open, High, Low, Close, and Volume is computed.
LSTM Model: A sequential deep learning model is built using LSTM layers (with Keras) to predict future stock prices.
