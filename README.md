# Stock-Price-Prediction-using-Time-Series-Forecasting
This project aims to predict future stock prices based on historical data, leveraging time series forecasting techniques. The goal is to analyze historical price data, identify patterns, and build a model that can forecast stock prices for the next 30 days.
# Project Overview
# Skills Developed: Time series analysis, feature engineering, and predictive modeling
# Tools & Libraries: Python, Pandas, Prophet, Statsmodels, Matplotlib

# Introduction
Stock price prediction is a challenging task due to the inherent volatility and randomness in financial markets. This project attempts to forecast stock prices using time series forecasting methods, focusing on identifying trends, seasonality, and volatility in the data.

# Data Collection
The stock data was collected from Yahoo Finance using the yfinance Python library. 

# Exploratory Data Analysis (EDA)
In the EDA phase, I examined the historical stock data to understand trends, seasonality, and volatility. This includes visualizing the closing price over time and calculating basic statistics.

# Time Series Decomposition
Using statsmodels,I decomposed the time series into three components:
# Trend - Long-term direction of the stock price.
# Seasonality - Regular, repeating patterns due to market cycles.
# Residuals - Random noise not explained by trend or seasonality.

# Modeling and Forecasting
I have used Facebook Prophet to forecast stock prices. Prophet is well-suited for time series data with clear trends and seasonal patterns.

# Steps:
1. Prepare Data: Prophet requires a specific format, with columns labeled ds (date) and y (target variable).
2. Fit the Model
3. Forecast Future Prices: I have created a future DataFrame to extend 30 days beyond the current data and generate predictions.
4. Results and Evaluation:
The model outputs a forecasted DataFrame that includes predictions along with uncertainty intervals. I have plotted the forecast to visualize predicted trends and compared it with actual values to evaluate performance.

# Conclusion
This project demonstrates a basic approach to stock price prediction using time series forecasting. By decomposing the data and using a model that captures trend and seasonality, I built a reasonably accurate forecast for short-term stock prices.

# Future Work
Experimenting with additional models like SARIMA or LSTM.
Using ensemble methods to combine predictions from multiple models.
Incorporating other features, such as trading volume or external economic indicators.
