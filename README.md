# Empirical-Asset-Pricing-and-Volatility-Analysis

This project performs statistical and time series analysis on two U.S. equity indices using daily market data. The objective is to analyze return behavior, volatility characteristics, distribution properties, and basic technical indicators using Python.

---

## Overview

This script:

- Downloads daily historical data using `yfinance`
- Computes daily percentage and log returns
- Generates descriptive statistics
- Calculates skewness and kurtosis
- Measures correlation between indices
- Computes rolling moving averages
- Visualizes price and return dynamics

The dataset includes more than one trading year (252+ observations) to ensure statistical relevance.

---

## Methods

### Data Collection
Daily closing prices are retrieved directly from Yahoo Finance.

### Return Calculations
- Arithmetic daily returns
- Log (continuously compounded) returns

### Statistical Analysis
- Mean
- Median
- Variance
- Standard deviation
- Skewness
- Kurtosis
- Correlation

### Technical Indicators
- 20-day rolling moving averages for trend analysis

### Visualization
- Price time series plots
- Moving average overlays
- Return distribution insights

---

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- scipy
- statsmodels
- arch

---

## Installation

Install dependencies with:

```bash
pip install yfinance pandas numpy matplotlib scipy statsmodels arch
```

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourrepo.git
   ```

2. Navigate into the project directory:
   ```bash
   cd yourrepo
   ```

3. Run the notebook or Python script.

---

## Key Takeaways

This project demonstrates:

- Financial return construction and interpretation
- Analysis of non-normal return distributions
- Volatility and tail risk evaluation
- Basic technical indicator implementation
- Applied quantitative finance using Python

---

**Author:** Miles Choquette  
M.S. Quantitative Finance | Computer Science Background
