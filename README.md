# Quantitative-Portfolio-Optimization
Title: Data-Driven Portfolio Optimization using Random Forest and Monte Carlo Simulation

Description:
This project explores quantitative portfolio optimization by combining traditional financial theory with modern machine learning techniques. It enhances the classical Modern Portfolio Theory (MPT) approach using Random Forest Regression and Monte Carlo simulations to model, analyze, and compare multiple investment strategies.

Objective:
To optimize asset allocation by maximizing the Sharpe Ratio through both predictive (machine learning) and statistical (MPT) methods and compare their performance under uncertainty.

Key Features:

Fetches historical stock data using yfinance

Implements Modern Portfolio Theory to compute expected return and volatility

Enhances predictions using Random Forest Regression

Simulates 10,000+ portfolios using Monte Carlo methods

Calculates and compares Sharpe Ratios across models

Visualizes the efficient frontier and portfolio distributions

Technologies Used:

Python

yfinance

NumPy, Pandas, Matplotlib, Seaborn

Scikit-learn (RandomForestRegressor)

SciPy (optimization)

Methods and Workflow:

Download stock data using yfinance

Calculate log returns and expected performance metrics

Build Random Forest Regression model to predict portfolio returns

Run Monte Carlo simulations to generate a wide range of portfolio scenarios

Optimize the Sharpe Ratio using numerical optimization

Compare strategy outputs (MPT, ML, Simulation) on risk-adjusted basis

Visualize efficient frontiers and highlight optimal portfolios

Performance Metrics:

Sharpe Ratio (MPT-based): ~0.85

Sharpe Ratio (ML-based): ~0.42

Sharpe Ratio (Simulation-based): ~1.25

Simulation count: 10,000+ portfolios

Project Structure:

QuantPortfolio_RF_Enhanced.ipynb — Main Jupyter Notebook

Outputs: Visual plots, Sharpe comparisons, asset allocation summaries

How to Run:

Clone the repository

Install dependencies (pip install -r requirements.txt)

Run the notebook in Jupyter or Colab

Set your stock tickers and time window in the code

View results and plots directly in the notebook
