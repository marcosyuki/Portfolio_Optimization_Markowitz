# Stock Portfolio Optimization

This project involves optimizing a stock portfolio using historical stock price data. The goal is to determine the best combination of stocks to maximize the Sharpe ratio, which balances the expected return against risk (volatility). The project includes analyzing the performance of individual stocks, calculating the covariance matrix, simulating multiple portfolios, and identifying the portfolio with the best Sharpe ratio. Additionally, the efficient frontier is calculated and visualized.

## Key Features:
- **Stock Data Retrieval:** Utilized the `yfinance` library to download historical adjusted close prices for a list of specified stocks.
- **Performance Analysis:** Calculated the daily logarithmic returns and annualized performance for each stock.
- **Portfolio Simulation:** Simulated a large number of portfolios with random weights, calculating the expected return, volatility, and Sharpe ratio for each.
- **Optimization:** Identified the portfolio with the maximum Sharpe ratio and determined the optimal stock weights.
- **Efficient Frontier:** Plotted the efficient frontier, showing the optimal trade-off between risk and return.

## Python Libraries:
- **yFinance** (`import yfinance as yf`)
  - For accessing financial data from Yahoo Finance
- **NumPy** (`import numpy as np`)
  - For numerical computing and handling arrays
- **Matplotlib** (`import matplotlib.pyplot as plt`)
  - For data visualization and plotting
  - **Matplotlib Ticker** (`import matplotlib.ticker as mtick`)
    - For customizing axis ticks and labels
- **Datetime** (`import datetime as dt`)
  - For handling dates and times
- **Pandas** (`import pandas as pd`)
  - For reading, manipulating, and analyzing data
- **SciPy** (`from scipy.optimize import minimize`)
  - For optimization tasks, such as minimizing a function


------------------------
 
![image](https://github.com/user-attachments/assets/4a8d8a1c-ab2f-40d9-8681-4c715701f517)

![image](https://github.com/user-attachments/assets/dbf61109-a8da-403d-820a-20bd3f2bba49)

![image](https://github.com/user-attachments/assets/a9ddba6f-6adb-49f5-999d-8dc01367201f)
