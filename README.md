# Multi-Asset Portfolio Optimization Engine

## Project Overview

This project develops a quantitative portfolio optimization framework using Python, Modern Portfolio Theory (MPT), and historical market data obtained through yFinance.

The objective is to evaluate the risk-return characteristics of a diversified multi-asset portfolio and identify optimal asset allocations through Monte Carlo simulation.

The framework analyzes equities, bonds, and gold to construct portfolios that maximize risk-adjusted returns while minimizing portfolio volatility.

---

## Asset Universe

| Ticker | Asset Class           |
| ------ | --------------------- |
| SPY    | US Equities           |
| FTAL.L | UK Equities           |
| GLD    | Gold                  |
| IEGA.L | Euro Government Bonds |

---

## Methodology

1. Download and clean historical market data using yFinance.
2. Calculate daily returns and annualized performance metrics.
3. Build covariance and correlation matrices.
4. Simulate 10,000 random portfolio allocations.
5. Calculate portfolio return, volatility, and Sharpe Ratio.
6. Identify:

   * Maximum Sharpe Ratio Portfolio
   * Minimum Variance Portfolio
7. Visualize the Efficient Frontier.

---

## Key Results

| Portfolio        | Expected Return | Volatility | Sharpe Ratio |
| ---------------- | --------------- | ---------- | ------------ |
| Maximum Sharpe   | 15.96%          | 11.41%     | 1.05         |
| Minimum Variance | 1.03%           | 5.71%      | -0.52        |

---

## Key Findings

* Gold delivered the strongest historical return during the sample period.
* Bonds reduced overall portfolio volatility despite weak standalone performance.
* Diversification lowered portfolio risk through low cross-asset correlations.
* The Maximum Sharpe portfolio achieved the strongest risk-adjusted performance.
* Monte Carlo simulation successfully mapped the Efficient Frontier and identified optimal allocation structures.

---

## Skills Demonstrated

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Financial Data Analysis
* Portfolio Optimization
* Monte Carlo Simulation
* Modern Portfolio Theory (MPT)
* Risk Management
* Quantitative Finance

---

## Repository Contents

* Jupyter Notebook containing the full analysis
* Efficient Frontier visualization
* Correlation heatmap
* Normalized asset performance chart
* Portfolio optimization memo

---

### Author

Busra Akkaya

Project completed as part of a self-directed quantitative finance and portfolio analytics learning portfolio.
