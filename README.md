# Quantitative Cryptocurrency Trading Strategy

This repository contains a Python implementation of a quantitative trading strategy focused on cryptocurrency markets. The strategy uses historical price and volume data to generate signals, manage portfolio weights, and evaluate performance.

## Features

- **Data Fetching**: Utilizes Binance API for historical cryptocurrency data
- **Signal Generation**: Computes volume-adjusted momentum signals
- **Risk Management**: Implements stop-loss and dynamic portfolio weighting
- **Backtesting Engine**: Includes transaction costs and return analysis
- **Visualization Tools**: Comprehensive performance and metrics plotting
- **Performance Analytics**: Calculates Sharpe ratios, drawdowns, and statistics

## Supported Cryptocurrencies

- BTC/USDT
- ETH/USDT
- BNB/USDT
- SOL/USDT
- ADA/USDT

## Prerequisites

- Python 3.8+
- Required libraries:
  ```
  pandas
  numpy
  matplotlib
  seaborn
  binance
  ```

## Installation

```bash
pip install pandas numpy matplotlib seaborn binance
```

## Setup

1. Clone the repository
2. Configure Binance API credentials
3. Run the Python script for backtesting

## Core Components

- **Data Pipeline**: Historical data fetching
- **Signal Generator**: Trading signal computation
- **Portfolio Manager**: Dynamic weight optimization
- **Performance Evaluator**: Strategy analysis and metrics

## Visualization Features

- Price and volume trend analysis
- Return distribution plots
- Portfolio weight allocation timeline
- Strategy vs BTC/USD performance comparison

## Performance Metrics

| Metric | Value |
|--------|--------|
| Gross Return | 1,137.37% |
| Net Return | 769.64% |
| BTC Return | 326.02% |
| Gross Sharpe Ratio | 1.93 |
| Net Sharpe Ratio | 1.69 |
| Maximum Drawdown | -29.11% |
| Monthly Win Rate | 58.33% |
