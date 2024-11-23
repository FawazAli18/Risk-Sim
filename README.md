# Risk-Sim
This repository contains a implementation of a Monte Carlo Simulation for assessing the risk and performance of a stock portfolio over time. Using historical stock data, the project evaluates portfolio value fluctuations and computes risk measures such as Value at Risk (VaR) and Conditional Value at Risk (CVaR).

Features

Stock Data Retrieval:
Automatically downloads historical stock data using Yahoo Finance.
Calculates daily percentage returns, mean returns, and covariance matrix for selected stocks.

Monte Carlo Simulation:
Simulates portfolio growth over a specified timeframe.
Models correlated daily returns using the Cholesky decomposition.

Risk Analysis:
Computes key risk metrics:
VaR (Value at Risk): Estimates potential loss at a specific confidence level.

CVaR (Conditional Value at Risk): Calculates average loss exceeding VaR.

Visualization:
Graph portfolio simulations over the simulation period for visual insight.
