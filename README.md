# A-Share Stock Backtesting and Analysis

This repository contains a Jupyter Notebook for backtesting and analyzing stock data using various financial metrics and technical indicators. The notebook leverages historical stock data to compute volatility, turnover rates, and other derived features to classify stocks and visualize their performance.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Results](#results)
- [License](#license)

## Introduction

This project aims to provide a comprehensive analysis of selected stocks over a specified period. It involves downloading historical stock data, calculating key metrics such as volatility and turnover rates, and visualizing these metrics to aid in investment decisions.

## Features

- **Data Loading**: Downloads historical stock data for multiple stocks from Yahoo Finance.
- **Volatility Calculation**: Computes the historical volatility of each stock.
- **Technical Indicators**: Adds various technical indicators, including scaled closing prices, returns, historical volatility, and volume volatility.
- **Categorization**: Classifies stocks based on their volatility into low, medium, and high categories.
- **Visualization**: Provides visualizations to compare the performance and volatility of different stocks.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- yfinance

You can install the required packages using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn yfinance
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/stock-backtesting-analysis.git
   ```

2. Navigate to the repository:

   ```bash
   cd stock-backtesting-analysis
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook BackTest_WL.ipynb
   ```

4. **Run the cells**: Execute the cells in the notebook sequentially to download data, perform calculations, and generate visualizations.

## Data Sources

- Historical stock data is sourced from Yahoo Finance using the `yfinance` library.
- Stock symbols and associated metadata are loaded from an Excel file (`Stocks.xlsx`) containing a watchlist sheet.

## Results

The notebook provides a detailed analysis of the selected stocks, including:

- Volatility and turnover rate calculations.
- Classification of stocks based on volatility.
- Visualization of technical indicators and stock performance.

## License

This project is licensed under the MIT License. See the LICENSE file for details.