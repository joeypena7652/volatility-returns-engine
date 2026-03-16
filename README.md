# volatility-returns-engine

A Python tool that downloads historical adjusted stock prices and computes returns and risk metrics, exporting CSV outputs and generating plots for quick comparison across tickers.

## What it does
• Downloads adjusted close prices for one or more tickers  
• Computes daily returns (simple or log)  
• Computes rolling annualized volatility  
• Computes max drawdown and summary metrics  
• Exports CSV files and saves plots

## Install
1 Create a virtual environment (optional)  
2 Install dependencies

```bash
pip install -r requirements.txt
