# Stock Technical Analysis with Python

This project demonstrates how to fetch historical stock data, calculate various technical indicators, and visualize them using Python in a Google Colab environment.

## Table of Contents
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Technical Indicators Used](#technical-indicators-used)
- [Data Source](#data-source)

## Features
- Fetches historical stock data for various tickers.
- Calculates popular technical analysis indicators like Simple Moving Average (SMA), Exponential Moving Average (EMA), Relative Strength Index (RSI), Moving Average Convergence Divergence (MACD), Linear Regression, and Candlestick Patterns (e.g., Engulfing).
- Visualizes stock prices and technical indicators using `matplotlib` and `mplfinance`.

## Setup
To run this notebook, you need to install the following Python libraries:

```bash
!pip install TA-Lib
!pip install yfinance
!pip install mplfinance
```

## Usage
1. Run the `pip install` cells to ensure all necessary libraries are installed.
2. Execute the import statements.
3. Modify the `start` and `end` dates in the data fetching cells to analyze different time periods.
4. Run the data fetching cells for tickers like AAPL, GS, and TSLA.
5. Execute the cells to calculate and plot various technical indicators.

## Technical Indicators Used
- **SMA (Simple Moving Average):** Used to smooth out price data over a specified period.
- **EMA (Exponential Moving Average):** Similar to SMA but gives more weight to recent prices.
- **RSI (Relative Strength Index):** A momentum oscillator that measures the speed and change of price movements.
- **MACD (Moving Average Convergence Divergence):** A trend-following momentum indicator that shows the relationship between two moving averages of a security's price.
- **LINEARREG (Linear Regression):** Provides a linear approximation of the price trend.
- **CDLENGULFING (Engulfing Candlestick Pattern):** Identifies bullish or bearish engulfing patterns in candlestick charts.

## Data Source
Historical stock data is sourced using the `yfinance` library, which pulls data from Yahoo Finance.
