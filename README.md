# LSTM-GARCH-SPY
Recurrent Neural Network LSTM+GARCH aimed to predict SPY for trading purposes

# 🧠 LSTM + GARCH Framework for SPY ETF Forecasting

This project aims to develop a quantitative finance framework for forecasting the SPY ETF price dynamics by combining LSTM neural networks with a GARCH overlay to capture volatility clustering and market dynamics.

## Project Objective
- Predict the future direction of the SPY ETF.
- Combine deep learning models (LSTM) with a GARCH model for volatility estimation.
- Integrate relevant macroeconomic and market features (VIX, AAPL, NVDA).
- Compare 8 different LSTM architectures using various loss functions (MSE, Huber Loss).

## Technologies & Tools
- Python 3.x
- TensorFlow / Keras
- statsmodels
- pandas / numpy / scipy
- matplotlib

## Model Inputs
- SPY ETF historical time series (lagged)
- VIX index
- Historical prices of AAPL and NVDA
- Volatility overlay estimated through GARCH models

## Model Outputs
- Forecast of SPY ETF future direction
- Model evaluation through RMSE metrics and graphical analysis
- Practical usage for trading decision support


## Setup Instructions
1. Create a virtual environment
```bash
pip install -r requirements.txt
