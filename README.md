# Trader-Performance-vs-Market-Sentiment-Task-0
Trader Performance vs Market Sentiment

This is an analysis of how market sentiments like fear and greed includes trade, its performance, its profits and losses, and wins. Two real-world datasets are used in the process. The goal is to uncover patterns in trade, connecting sentiment signals to trader actions like position sizing and trade frequency.

## Objective

To explore the relationship between Bitcoin market sentiment and:
-Trader performance (PnL, win rate, risk exposure)
-Behavioral patterns (frequency, leverage, long/short bias)
-Distinct trader segments

## Datasets
1) Bitcoin Market Sentiment (Fear/Greed)
Columns: Date, Classification (Fear / Greed)
Link: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

2) Historical Trader Data (Hyperliquid)
Includes fields like: account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, etc.
Link: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

Methodology
-Data Preparation
Cleaned and inspected both datasets
Handled missing values and duplicates
Converted timestamps and aligned data at daily level

-Engineered key metrics:
Daily PnL
Win rate
Trade frequency
Position size
Leverage proxy
Long/Short ratio

-Analysis
1. Performance vs Sentiment
Compared PnL, win rate, and risk (drawdown proxy) across Fear and Greed periods
2. Behavioral Changes
-Analyzed how traders adjust:
Trade frequency
Position sizes
Long/Short bias
Risk exposure
3. Trader Segmentation
-Identified key trader groups:
Frequent vs Infrequent traders
High vs Low risk (position size / leverage proxy)
Consistent vs Inconsistent performers

## Key Insights
Higher trading activity during Fear
→ Indicates panic-driven or reactive behavior under uncertainty
Position sizing varies with sentiment
→ Traders exhibit different risk appetites in Fear vs Greed phases
Behavioral bias in trade direction
→ Long/Short preferences shift based on market sentiment 

## Strategy Recommendations
Reduce trade frequency during high-volatility Fear phases to avoid overtrading
Adjust position sizes based on sentiment to manage risk exposure

## Tech Stack
Python
Pandas
NumPy
Matplotlib
Kaggle
Jupyter Notebook 

## How to Run
pip install pandas numpy matplotlib
jupyter notebook

