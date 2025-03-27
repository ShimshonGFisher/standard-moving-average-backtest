# Moving Average Strategy Backtest

This project simulates a simple trading strategy using a triple moving average crossover system (SMA20, SMA50, SMA200) on historical stock data (AAPL). It shows how rules-based signals can be used to generate buy/sell trades and simulate portfolio performance over time.

---

##  What It Does

-  Downloads real stock data from Yahoo Finance using `yfinance`
-  Calculates SMA20, SMA50, SMA200 using pandas
-  Creates buy/sell signals based on SMA crossover logic
-  Simulates a $10,000 trading portfolio using those signals
-  Plots price + signals + portfolio value over time

---

##  What I Learned

- How to use rolling averages in pandas
- How to simulate trade logic with buy/sell triggers
- How to track portfolio value step by step
- How to use matplotlib for financial charting
- How to debug, iterate, and structure a quant strategy

---

##  Tools Used

- Python
- pandas
- matplotlib
- yfinance
- Jupyter Notebook and Colab

---

##  Next Steps

- Add comparison to buy-and-hold benchmark
- Test on other tickers (e.g. TSLA, SPY, NVDA)
- Add risk metrics (Sharpe ratio, drawdown)
- Build an interactive app version (using Streamlit or Dash)

---

## 🧑‍💻 Author

Built by ShimshonGFisher
