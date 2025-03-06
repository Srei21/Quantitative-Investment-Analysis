# Quantitative-Investment-Analysis


## Overview

This repository contains Jupyter notebook focused on quantitative analysis of stocks. The analysis combines financial data retrieval, exploratory data analysis, and machine learning techniques to provide insights into stock performance and potential predictive factors.

## Key Features

1. **Data Collection**: Utilizes yfinance to fetch 5 years of historical stock data for consumer discretionary companies.
2. **Exploratory Data Analysis (EDA)**:
    - Visualizes cumulative returns of stocks over time.
    - Provides insights into stock performance trends.
3. **Feature Engineering**:
    - Calculates key financial metrics including P/E ratio, market cap, and beta.
    - Prepares data for machine learning model input.
4. **Machine Learning Model**:
    - Implements Ridge Regression for stock return prediction.
    - Uses train-test split for model evaluation.
5. **Model Evaluation**:
    - Assesses model performance using Mean Squared Error (MSE) and R-squared metrics.
6. **Feature Importance Analysis**:
    - Identifies influential factors in stock return prediction based on Ridge Regression coefficients.
7. **Risk Analysis**:
    - Calculates beta for each stock relative to the S\&P 500 (SPY) to assess market sensitivity.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required libraries: yfinance, pandas, numpy, scikit-learn, matplotlib


## Usage

1. Clone the repository.
2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Open the Jupyter notebook `Consumer_Discretionary.ipynb`.
4. Run the cells sequentially to perform the analysis.

## Future Enhancements

- Implement additional machine learning models for comparison.
- Incorporate more advanced feature engineering techniques.
- Develop a comprehensive backtesting framework.
- Expand analysis to include sector-wide trends and insights.
