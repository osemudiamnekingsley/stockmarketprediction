# Stock Price Prediction Project

## Overview
This project involves time series analysis and stock price prediction using three different models: ARIMA, LSTM, and XGBoost. The goal is to compare the performance of these models in capturing market trends and predicting future prices.

## Data Source
The stock price data was obtained from Yahoo Finance, consisting of historical closing prices.

## Models Used

- **ARIMA (AutoRegressive Integrated Moving Average)**  
  ARIMA is suitable for linear time series data and primarily used for trend analysis. It demonstrated decent trend-following capabilities but struggled with sudden price fluctuations.

- **LSTM (Long Short-Term Memory)**  
  LSTM is a deep learning model designed to capture long-term dependencies and patterns in sequential data. LSTM performed the best, accurately tracking price movements with some lag.

- **XGBoost (Extreme Gradient Boosting)**  
  XGBoost is a powerful machine learning model used for regression tasks. It underperformed, providing flat predictions, indicating the need for further feature engineering and hyperparameter tuning.

## Results Summary
- **ARIMA**: Effective for trend-following but struggled with sudden changes in stock prices.
- **LSTM**: Outperformed the other models, offering more accurate predictions by identifying complex patterns over time.
- **XGBoost**: Provided flat predictions and required more refinement in terms of feature engineering and hyperparameter tuning.

## Conclusion
LSTM is the most suitable model for stock price prediction in this project, given its ability to capture complex temporal patterns. Further improvements can be explored by fine-tuning the model and using additional data features.

## Requirements
- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- XGBoost
- Statsmodels

## Acknowledgements
- Data sourced from Yahoo Finance.
- Libraries used for analysis and visualization.
