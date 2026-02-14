# Empirical-Asset-Pricing-and-Volatility-Analysis

Financial Time Series Analysis of Two Equity Indices

This project performs a statistical and time series analysis of two major U.S. stock market indices using daily data from Yahoo Finance. The analysis focuses on return behavior, distributional properties, correlation structure, and basic technical indicators.

Overview

The script:

Downloads daily historical price data using yfinance

Computes arithmetic and log returns

Generates descriptive statistics

Measures skewness and kurtosis

Calculates rolling moving averages

Visualizes price dynamics and trends

Explores volatility characteristics

The dataset contains more than 252 daily observations to ensure statistical relevance.

Objectives

The goal of this analysis is to:

Compare return distributions between two equity indices

Evaluate volatility and risk characteristics

Assess correlation between indices

Examine distribution shape (normality, skewness, fat tails)

Explore trend-following indicators using moving averages

Methods & Tools
Libraries Used

yfinance

pandas

numpy

matplotlib

scipy

statsmodels

arch (for volatility modeling)

Statistical Measures Computed

Mean

Median

Variance

Standard Deviation

Skewness

Kurtosis

Correlation

Both percentage returns and log returns are analyzed.

Key Features
1. Data Retrieval

Daily closing prices are downloaded directly from Yahoo Finance.

2. Return Calculations

Percentage daily returns

Log returns (continuously compounded returns)

3. Descriptive Statistics

Summary statistics help compare central tendency, dispersion, and higher moments of the distributions.

4. Distribution Analysis

Skewness identifies asymmetry

Kurtosis measures tail risk

Interpretation of whether distributions are mesokurtic or leptokurtic

5. Rolling Moving Averages

20-day moving averages are computed and plotted to:

Identify trends

Illustrate smoothing effects

Demonstrate basic technical trading concepts

6. Visualization

Time series plots show:

Daily index levels

Moving average overlays

Return dynamics

What This Project Demonstrates

Understanding of financial return construction

Ability to analyze non-normal return distributions

Interpretation of volatility and tail risk

Application of technical indicators

Proficiency in Python for financial data analysis

How to Run

Install required packages:

pip install yfinance pandas numpy matplotlib scipy statsmodels arch


Run the notebook or script in a Python environment.

Potential Extensions

GARCH volatility modeling

Value at Risk (VaR) estimation

Sharpe ratio comparison

Hypothesis testing for mean differences

Autocorrelation diagnostics

Backtesting moving average strategies

