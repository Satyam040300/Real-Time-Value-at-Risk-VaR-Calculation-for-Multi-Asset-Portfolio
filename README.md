# Real-Time Value at Risk (VaR) Calculation for Multi-Asset Portfolio

## Overview

This project calculates the **Value at Risk (VaR)** for a multi-asset portfolio consisting of Apple (AAPL) and Microsoft (MSFT) stocks. The VaR is estimated using the **Variance-Covariance method** to calculate the potential loss in the portfolio's value over a specific period (10 days) at a given confidence level (99%).

### Key Features:
- Real-time fetching of stock data (prices, volatilities, correlations) using the `yfinance` library.
- Calculation of 10-day VaR at a 99% confidence level.
- Portfolio consisting of two assets (AAPL and MSFT) with configurable weights.
- Adjustable confidence levels (99%, 95%) for VaR calculation.

## Technical Stack
- **Python** (Programming Language)
- **NumPy** (Numerical Computing)
- **yFinance** (Real-Time Stock Data)
- **Pandas** (Data Processing)

## Usage

### 1. Fetch Real-Time Stock Data
The script dynamically fetches real-time stock data for Apple (AAPL) and Microsoft (MSFT).

### 2. Calculate Volatility and Correlation
- **Volatility** is estimated using the historical daily price changes over the past year.
- The **correlation** between the two stocks is calculated based on their price changes.

### 3. VaR Calculation
The **Variance-Covariance method** is used to compute the portfolio's 10-day VaR at the given 99% confidence level.

### 4. Script Execution

To run the script, execute the Python file. This will output the 10-day VaR for the portfolio with a 99% confidence level.

python Satyam_Real-Time_Value_at_Risk_VaR_Calculation_for_Multi_Asset_Portfolio.py

The 99% 10-day VaR for the portfolio is: 0.XXXX

## Author
Satyam

University at Buffalo
School of Management
MS in Business Analytics (Finance)
