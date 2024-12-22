NVDA Stock Market Data Analysis
This project analyzes NVIDIA Corporation (NVDA) stock market data over the past year using Python. It evaluates key performance metrics, moving averages, RSI indicators, and identifies bullish and bearish trends. Below is a summary of the analysis.
1. Stock Performance
•	Percentage Change: The stock price increased by 175.03% over the past year, indicating strong market performance.
•	Daily Volatility: The average daily volatility was 3.30%, reflecting moderate-to-high price fluctuations.
•	Bullish vs. Bearish Days:
o	140 Bullish Days (positive daily returns).
o	110 Bearish Days (negative daily returns).
2. Moving Average Analysis
The analysis includes two key moving averages:
•	20-Day Moving Average (Short-Term Momentum)
•	50-Day Moving Average (Longer-Term Trend)
Key Findings:
•	Golden Cross (Bullish Signal): Occurs when the 20-day MA crosses above the 50-day MA.
o	Identified 3 Bullish Crosses signaling upward momentum.
•	Death Cross (Bearish Signal): Occurs when the 20-day MA crosses below the 50-day MA.
o	Identified 4 Bearish Crosses signaling potential downward trends.
The visualization highlights these crossovers, providing insights into trend changes and market momentum.
3. RSI (Relative Strength Index) Analysis
The RSI indicator was used to detect overbought and oversold conditions:
•	RSI > 70 (Overbought): Detected 84 instances, indicating potential bearish reversals due to overvaluation.
•	RSI < 30 (Oversold): Detected 5 instances, suggesting rare undervaluation and potential bullish reversals.
The RSI plot highlights periods of extreme momentum shifts and helps contextualize price trends.

Visualizations
•	Closing Price Trend: Shows NVDA’s growth trajectory and key crossover points.
•	Moving Averages: Highlights Golden and Death Crosses to identify bullish and bearish periods.
•	RSI Indicator: Annotates overbought/oversold levels to explain momentum shifts.
________________________________________
Tools and Libraries
•	pandas for data manipulation and calculations.
•	matplotlib for data visualization.
•	yfinance for fetching historical stock data.
________________________________________
Key Insights
•	NVDA stock demonstrated robust growth with consistent bullish momentum over the last year.
•	Short-term corrections (identified via RSI and Death Crosses) were infrequent, reinforcing a strong upward trend.
•	The combination of moving averages and RSI offers valuable insights for traders looking to time entries and exits.

