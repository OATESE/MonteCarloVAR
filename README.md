# Value at Risk (VaR) Monte Carlo Simulation

## Overview

This repository contains a project focused on measuring the Value at Risk (VaR) for investments in options on Procter and Gamble (PG) stock using Monte Carlo simulation. The project aims to compute the VaR at a 75% confidence level for both a call option and the underlying stock.

## Project Details

### Objective

As a risk analyst for an investment bank, the task is to analyze the risk of an investment in PG stock options and estimate the VaR for a call option and the underlying stock, incorporating expected returns and dividends in the simulation.

### Methodology

1. **Data Collection**: 
   - Historical adjusted close price data for PG stock from Yahoo Finance.
   - Option contract data from CBOE with a maturity date closest to three months.

2. **Monte Carlo Simulation**:
   - Generate simulated price paths for the underlying stock.
   - Calculate daily log returns and estimate daily volatility.
   - Use the simulated price paths to estimate the distribution of returns and compute the VaR.

3. **Sensitivity Analysis**:
   - Analyze the impact of different volatility levels on the VaR estimates.

### Key Components

- **Data**: Historical stock prices and option contract details.
- **Simulation**: Stochastic process model for generating price paths.
- **Analysis**: Frequency distribution of simulated returns, VaR calculation, and sensitivity analysis.

## Submission

The complete project report, detailing the methodology, data, results, and analysis, is available in the repository. You can view the [submission file here](https://github.com/OATESE/G10-Momentum-Trading-Strategy-/blob/main/VAR%20Monte%20Carlo.pdf).

## Repository Structure

- **README.md**: This file.
- **VAR Monte Carlo.pdf**: The full project report with detailed analysis and results.

## Conclusion

This project demonstrates the use of Monte Carlo simulation to estimate the VaR for an investment in PG stock options, providing insights into the risk profile of such investments and highlighting the importance of robust risk management practices.
