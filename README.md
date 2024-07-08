# A-Share Quantitative Trading Strategy With Backtesting

This repository showcases a sophisticated quantitative trading strategy implemented in a Jupyter Notebook. The strategy leverages historical stock data, computes essential financial metrics, and derives technical indicators to aid in backtesting and performance analysis. This project reflects my expertise in quantitative finance, data analysis, and algorithmic trading.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technical Stack](#technical-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Results](#results)
- [License](#license)

## Introduction

The primary objective of this project is to develop and backtest a quantitative trading strategy using historical stock data. By calculating key financial metrics such as volatility and turnover rates, and applying various technical indicators, this project aims to provide insightful analysis to enhance trading decisions.

## Features

- **Historical Data Download**: Fetches historical stock data for multiple equities from Yahoo Finance.
- **Volatility and Turnover Calculation**: Computes historical volatility and turnover rates for each stock.
- **Technical Indicators**: Integrates a suite of technical indicators, including scaled closing prices, returns, historical volatility, and volume volatility.
- **Stock Classification**: Categorizes stocks based on volatility into low, medium, and high.
- **Backtesting Framework**: Implements a backtesting mechanism to evaluate the trading strategy.
- **Visualization**: Provides comprehensive visualizations to compare stock performance and analyze strategy outcomes.

## Technical Stack

- **Programming Language**: Python 3.x
- Libraries:
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
  - Financial Data: `yfinance`

You can install the required packages using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn yfinance
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Yiyang-Xu/A-Share-Volatility-Trading-Strategy.git
   ```

2. Navigate to the repository:

   ```bash
   cd A-Share-Volatility-Trading-Strategy
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook BackTest_WL.ipynb
   ```

4. **Run the cells**: Execute the cells in the notebook sequentially to download data, perform calculations, and generate visualizations.

## Data Sources

- **Yahoo Finance**: Historical stock data is sourced using the `yfinance` library.
- **Excel File**: Stock symbols and metadata are loaded from an Excel file (`Stocks.xlsx`) containing a watchlist sheet.

## Results

The notebook presents a detailed quantitative analysis, including:

- Computation of volatility and turnover rates.
- Classification of stocks based on their volatility.
- Integration of technical indicators.
- Visual and statistical analysis of the trading strategy's performance.

## License

This project is licensed under the MIT License. See the LICENSE file for details.