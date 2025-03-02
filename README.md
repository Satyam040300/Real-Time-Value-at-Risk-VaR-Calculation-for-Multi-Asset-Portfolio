Real-Time Value at Risk (VaR) Calculation for Multi-Asset Portfolio

Overview

This project calculates the Value at Risk (VaR) for a multi-asset portfolio consisting of Apple (AAPL) and Microsoft (MSFT) stocks. The VaR is estimated using the Variance-Covariance method to calculate the potential loss in the portfolio's value over a specific period (10 days) at a given confidence level (99%).

Key Features:

Real-time fetching of stock data (prices, volatilities, correlations) using the yfinance library.
Calculation of 10-day VaR at a 99% confidence level.
Portfolio consisting of two assets (AAPL and MSFT) with configurable weights.
Adjustable confidence levels (99%, 95%) for VaR calculation.

Technical Stack

Python (Programming Language)
NumPy (Numerical Computing)
yFinance (Real-Time Stock Data)
Pandas (Data Processing)

Installation

To run the project, you need to install the following dependencies. You can install them using pip:
bash
Copy
Edit
pip install yfinance numpy

Usage

1. Fetch Real-Time Stock Data
The script dynamically fetches real-time stock data for Apple (AAPL) and Microsoft (MSFT).

2. Calculate Volatility and Correlation
Volatility is estimated using the historical daily price changes over the past year. The correlation between the two stocks is calculated based on their price changes.

3. VaR Calculation
The Variance-Covariance method is used to compute the portfolio's 10-day VaR at the given 99% confidence level.

4. Script Execution

Run the Python script by executing the following command:
bash
Copy
Edit
Satyam_Real-Time Value at Risk (VaR) Calculation for Multi-Asset Portfolio.ipynb
This will output the 10-day VaR for the portfolio with a 99% confidence level.

Example Output

The output of the script will show the 10-day Value at Risk for the portfolio based on the current stock data:
The 99% 10-day VaR for the portfolio is: 0.XXXX
Where 0.XXXX is the calculated VaR value for the portfolio.

Variables

Portfolio Weights: The proportion of each stock in the portfolio (default is 50% each for AAPL and MSFT).
Portfolio Value: The total value of the portfolio (default is set to 1 for simplicity).
Confidence Level: The confidence level for VaR calculation (e.g., 99% or 95%).
Time Horizon: The number of days for which VaR is calculated (default is 10 days).

Future Improvements

Support for More Assets: Extend the model to support portfolios with more than two assets.
Additional VaR Models: Implement alternative VaR calculation methods like Historical Simulation or Monte Carlo Simulation.
Enhanced Data Visualization: Add visualizations for the portfolio's risk over time or VaR distribution.

Author

Satyam
University at Buffalo School of Management
MS in Business Analytics (Finance)



