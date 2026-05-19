Python-Based Value at Risk (VaR) Calculator

A quantitative risk analysis tool built in Python to measure portfolio downside exposure using multiple Value at Risk (VaR) methodologies utilising stock price data of NVIDIA, directly imported from Yahoo Finance. The model retrieves real historical market data and estimates potential portfolio losses under different statistical approaches.

Overview

This project was developed to simulate professional portfolio risk management practices by implementing three widely used VaR models:

Parametric VaR
Historical VaR
Monte Carlo VaR

Using historical stock data from Yahoo Finance, the system evaluates portfolio risk at a selected confidence level and estimates the maximum expected loss over a given time horizon.

Key Features
Real Market Data Integration
Retrieves historical stock prices using Yahoo Finance
Supports multi-asset portfolio analysis
Uses daily return calculations for risk estimation
Multi-Method VaR Analysis
Parametric VaR

Assumes normally distributed returns and calculates risk using:

Mean returns
Standard deviation
Z-score confidence intervals
Historical VaR

Uses actual historical portfolio returns to estimate downside risk without assuming normal distribution.

Monte Carlo VaR

Simulates thousands of potential portfolio outcomes using random return generation for probabilistic risk analysis.

Portfolio Risk Assessment
Custom portfolio allocation weights
Adjustable portfolio value
Configurable confidence levels
Simulation-based loss estimation
Tech Stack
Python
NumPy
Pandas
SciPy
yFinance
Quantitative Risk Modelling
Core Financial Concepts Used
Value at Risk (VaR)
Portfolio Risk Management
Statistical Modelling
Monte Carlo Simulation
Historical Return Analysis
Volatility Measurement
Quantitative Finance
Workflow
Retrieve historical stock price data
Calculate daily returns
Generate weighted portfolio returns
Compute:
Parametric VaR
Historical VaR
Monte Carlo VaR
Display estimated downside risk metrics
