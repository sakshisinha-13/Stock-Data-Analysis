# Stock-Performance-Analysis

## Overview
This project analyzes the stock performance of **INFY** using historical stock data. The analysis includes calculating key financial metrics, identifying trends, and providing actionable insights into the stock's volatility and performance.

## Features
- **Financial Metrics**:
  - Daily returns (percentage change between open and close prices)
  - Moving Averages (50-day and 200-day)
  - Volatility (30-day rolling standard deviation)
- **Trend Identification**:
  - Bullish and bearish trends based on moving averages
- **Visualizations**:
  - Stock closing price with moving averages
  - Candlestick charts for price action
  - Volatility over time
  - Distribution of daily returns

## Tools and Libraries
- **Python**:
  - `pandas` for data manipulation and analysis
  - `numpy` for numerical operations
  - `matplotlib` for data visualization
  - `mplfinance` for candlestick chart visualization
- **Google Colab**: For running the analysis and generating the visualizations

## Dataset
- **Name**: INFY Stock Data
- **Contents**:
  - Open, High, Low, Close prices
  - Adjusted Close price
  - Volume of stocks traded

## Insights
1. **Bullish Trends**: Periods where the 50-day moving average crossed above the 200-day moving average, indicating potential buy signals.
2. **Volatility**: Observed significant volatility based on the 30-day rolling standard deviation, highlighting high-risk periods.
3. **Average Daily Return**: The average daily return of **X%** suggests moderate growth potential for the stock.
4. **Recommendations**:
   - Consider buying during identified bullish trends for long-term growth.
   - Avoid trading during high volatility periods if you prefer a risk-averse strategy.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/sakshisinha-13/Stock-Performance-Analysis.git
