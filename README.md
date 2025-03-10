# # FINE3300-Stock-Analysis

This repository contains my code for Assignment 3 in FINE 3300. These program files analyze an index fund's price and volume over the month of January, and use technical indicators such as moving averages and Bollinger Bands to analyze Apple's stock price trends. Stock data will be processed from both a CSV file and Yahoo Finance, to visualize stock price trends.

## **Program Description**
The script retrieves and processes stock data for AAPL (Apple Inc.) and IVV (S&P 500 ETF) to analyze price trends and technical indicators.  
The analysis is divided into two parts:

**Part A: IVV Candlestick Chart**  
   - Retrieves IVV stock data from Yahoo Finance for January 2025.  
   - Cleans and processes the data for visualization.  
   - Plots a candlestick chart with volume bars to analyze price movements.  

**Part B: AAPL Stock & Bollinger Bands**  
   - Reads AAPL stock data from `StockData.csv`.  
   - Computes the 20-day Moving Average (MA).  
   - Calculates Bollinger Bands (Upper & Lower) to assess price volatility.  
   - Plots stock price trends with Bollinger Bands and moving averages.


## **Inputs**
- **Part A:** IVV Data from Yahoo Finance
- Data Source: `yfinance` API  
- Columns: Date, Open, High, Low, Close, Volume  

## **Part B:** AAPL Stock Data (CSV File)
- Data Source: `StockData.csv`  
- Columns: Trading Day, AAPL (Closing Prices)  

## **📌 Outputs**
- **Part A:** Candlestick Chart for IVV stock price trends
- **Part B:** Line chart showing:
  - AAPL Closing Price
  - 20-day Moving Average
  - Bollinger Bands (Upper & Lower)
  - Shaded Bollinger Band area
