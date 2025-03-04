**# Trade_Analysis**
Intraday Momentum Trading Strategy using Python & Backtrader
This project is a fully automated intraday trading strategy built with Backtrader, a powerful backtesting framework for Python. It focuses on NIFTY intraday trading using momentum-based entry and exit rules derived from historical price action. The strategy is designed to identify market trends, execute trades, and manage risk effectively.

**📌 Key Features:**
🔹 Volatility-Based Entry & Exit:

At 9:15 AM, the strategy calculates the daily volatility based on the previous high and low.
Defines an upper and lower boundary for entry based on volatility.
**🔹 Trade Execution Logic:**

If the previous close is above the upper boundary, it enters a long position (BUY).
If the previous close is below the lower boundary, it enters a short position (SELL).
Positions are taken at 9:30 AM and closed at 3:15 PM to avoid overnight risk.
**🔹 Risk Management:
**
Implements position sizing using lot size and number of lots.
Includes commission costs (0.3%) for realistic simulations.
Closes all positions at market close (3:15 PM) to avoid overnight exposure.
**🔹 Trade Logging & Performance Tracking:**

Logs entry/exit trades along with timestamps and contract details.
Tracks portfolio value, profit/loss, drawdowns, and run-ups.
Generates a detailed trade report with cumulative profit and trade statistics.
**🔹 Data Visualization Dashboard:**

Line Chart: Displays price movement, trade executions, and volatility boundaries.
Bar Chart: Shows profit/loss of each trade for performance evaluation.
📊 Tools & Technologies Used:
✅ Python (Pandas, NumPy, Matplotlib, Seaborn)
✅ Backtrader (Backtesting & Trading Logic)
✅ CSV Data Processing (NIFTY OHLC Data)
✅ Tkinter Backend (For GUI plotting)

**📥 How to Run the Code?**
1️⃣ Install dependencies:
pip install backtrader pandas matplotlib seaborn
2️⃣ Place your NIFTY OHLC data in C:/Users/Ninja/Trade/nifty_ohlc.csv.
3️⃣ Run the script:
python intraday_momentum.py
4️⃣ View the trade report & performance dashboard.

#AlgorithmicTrading #Python #Backtrader #StockMarket #DataScience #TradingBot 🚀
