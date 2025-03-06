# Stock-Picking Strategy

## Methodology

### Macro Opportunity Identification

- Recognized the 2022 tech stock decline as a buying opportunity for quality stocks at lower valuations.


### Sector \& ETF Analysis

- Analyzed S\&P 500 ETF and identified top three sectors based on median cumulative returns.


### Risk and Return Metrics Evaluation

- Computed and visualized cumulative returns, annualized volatility, and risk-return metrics over 10-year, 5-year, 3-year, and 1-year periods.


### Fundamental \& Quantitative Stock Selection

- Used recent fundamental data (financial ratios) and historical cumulative returns.
- Employed Optuna to balance metrics and select top 20 stocks in each sector.


### Robustness via Bootstrapping \& Lookback Optimization

- Applied bootstrapping with Optuna to determine optimal lookback period (10 years) for estimating return parameters.


### Multifactor Expected Return Estimation

- Replaced CAPM with Fama-French three-factor model.
- Retrieved Fama-French data online, resampled monthly data to daily, and converted percentages to decimals.
- Ran Ridge regressions with hyperparameter tuning via Optuna on daily excess returns for robust, multifactor expected annual returns.


### Portfolio Optimization via MPT

- Calculated annualized covariance matrix from 10-year stock return data.
- Simulated thousands of portfolios using multifactor expected returns and covariance matrix.
- Imposed constraint: each stock's weight at least 5%.
- Identified optimal portfolio with highest Sharpe ratio and visualized efficient frontier.


## Performance and Insights

### Portfolio Performance

- Significantly outperformed S\&P 500, with returns approximately 6 times higher.
- Key holdings: NFLX, NVDA, META, AMZN, producing over 134% YTD returns.


### MPT vs. Actual Portfolio

- MPT allocation more defensive.
- Actual portfolio recognized asymmetric risk-reward opportunity in tech after 2022 crash.
- Superior performance attributed to:

1. Seasonality and entry timing
2. Rate hike expectations already priced in
3. Historically undervalued tech stocks


### Validation

- Monte Carlo simulations confirmed portfolio's performance in higher return percentiles.


## Conclusion

The approach demonstrated the value of combining quantitative methods with strategic market insights. While MPT provided a baseline, the actual portfolio leveraged macroeconomic trends, valuation insights, and market timing to achieve superior returns.
