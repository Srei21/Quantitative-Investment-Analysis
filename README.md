# Quantitative-Investment-Analysis
Quantitative Investment Analysis: Consumer Discretionary Sector
Overview
This repository contains a Jupyter notebook focused on quantitative analysis of stocks in the consumer discretionary sector. The analysis combines financial data retrieval, exploratory data analysis, and machine learning techniques to provide insights into stock performance and potential predictive factors.

Key Features
Data Collection: Utilizes yfinance to fetch 5 years of historical stock data for consumer discretionary companies.

Exploratory Data Analysis (EDA):

Visualizes cumulative returns of stocks over time.

Provides insights into stock performance trends.

Feature Engineering:

Calculates key financial metrics including P/E ratio, market cap, and beta.

Prepares data for machine learning model input.

Machine Learning Model:

Implements Ridge Regression for stock return prediction.

Uses train-test split for model evaluation.

Model Evaluation:

Assesses model performance using Mean Squared Error (MSE) and R-squared metrics.

Feature Importance Analysis:

Identifies influential factors in stock return prediction based on Ridge Regression coefficients.

Risk Analysis:

Calculates beta for each stock relative to the S&P 500 (SPY) to assess market sensitivity.

Requirements
Python 3.x

Jupyter Notebook

Required libraries: yfinance, pandas, numpy, scikit-learn, matplotlib

Usage
Clone the repository.

Install the required dependencies:

text
pip install -r requirements.txt
Open the Jupyter notebook Consumer_Discretionary.ipynb.

Run the cells sequentially to perform the analysis.

Future Enhancements
Implement additional machine learning models for comparison.

Incorporate more advanced feature engineering techniques.

Develop a comprehensive backtesting framework.

Expand analysis to include sector-wide trends and insights.
