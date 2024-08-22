### Project Summary

**Title: Stock Portfolio Optimization**

This project involves optimizing a stock portfolio using historical stock price data. The goal is to determine the best combination of stocks to maximize the Sharpe ratio, which balances the expected return against risk (volatility). The project includes analyzing the performance of individual stocks, calculating the covariance matrix, simulating multiple portfolios, and identifying the portfolio with the best Sharpe ratio. Additionally, the efficient frontier is calculated and visualized.

### Key Features:
- **Stock Data Retrieval:** Utilized the `yfinance` library to download historical adjusted close prices for a list of specified stocks.
- **Performance Analysis:** Calculated the daily logarithmic returns and annualized performance for each stock.
- **Portfolio Simulation:** Simulated a large number of portfolios with random weights, calculating the expected return, volatility, and Sharpe ratio for each.
- **Optimization:** Identified the portfolio with the maximum Sharpe ratio and determined the optimal stock weights.
- **Efficient Frontier:** Plotted the efficient frontier, showing the optimal trade-off between risk and return.
