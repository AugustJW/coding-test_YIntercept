# coding-test_YIntercept

### 1. The profile "0.visul.ipynb"

This notebook presents a visual analysis of closing prices, trading volumes, and market capitalizations for each ticker over time. Additionally, it includes a visualization of market capitalization trends by sector. The visuals suggest a correlation between the closing prices of tickers and their respective sector market capitalizations.

### 2 The profile "0.simple.ipynb"

This notebook implements a straightforward trading strategy. On each trading day, it identifies the top 'k' stocks experiencing the most substantial changes in closing price, volume, and market capitalization relative to the previous day. These metrics are used to select stocks for potential trades, aiming to capitalize on short-term price movements.

### 3 The profile "0.forecasting.ipynb"

Drawing insights from "0.visual.ipynb," this notebook develops a CNN-based multivariate time series forecasting model. The model uses historical closing prices and sector market capitalizations as input variables to predict future closing prices. Post-prediction, the model selects the top 'k' stocks with the highest relative predicted closing price change from the previous day, forming the basis for a trading strategy.
