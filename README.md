# Trader Behavior vs Market Sentiment (Fear & Greed)

This project analyzes how crypto trader behavior changes across different market sentiment regimes (Fear vs Greed) using trade-level data and market sentiment indicators.

## 📌 Objective
To understand how profitability, trading activity, risk-taking, and decision efficiency vary during Fear and Greed periods in crypto markets.

## 📊 Datasets
- **Trader Data**: Historical trade-level data from the Hyperliquid platform  
- **Market Sentiment**: Bitcoin Fear & Greed Index (daily sentiment classification)

## 🧠 Analysis Overview
The analysis compares trader behavior across sentiment regimes using:
- Daily profitability (PnL)
- Trading volume
- Average trade size (risk per trade)
- Win rate (decision efficiency)

Trades were aggregated at a daily level and enriched with market sentiment to enable robust comparison.

## 📁 Repository Structure
ds_sarthak_shandilya/
├── notebook_1.ipynb
├── csv_files/
│   └── daily_metrics.csv
├── outputs/
│   ├── pnl_vs_sentiment.png
│   ├── volume_vs_sentiment.png
│   ├── avg_trade_size_vs_sentiment.png
│   └── win_rate_vs_sentiment.png
├── ds_report.pdf

## ▶️ How to View
- Open `notebook_1.ipynb` to see the full analysis workflow  
- Refer to `ds_report.pdf` for summarized insights and conclusions  
- Visual outputs are available in the `outputs/` directory  

## 🔗 Google Colab
The notebook was developed and executed in Google Colab.  
Access permissions are set to **Anyone with the link can view**.
