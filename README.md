# Stock Return Prediction Using Machine Learning

## Project Overview

This project aims to predict the return of a selected stock using various financial ratios and statistics, besides the stock's own price time series. The analysis is done in Python, leveraging data collected from Bloomberg/Refinitiv (LSEG Workspace) terminals. We perform data exploration, cleaning, and feature engineering, followed by training machine learning models to predict stock returns.

## Steps Involved

### 1. Data Collection
The first step involves selecting a stock from Bloomberg/Refinitiv and gathering various financial ratios and statistics about the stock, excluding the stock's price time series.
### 2. Data Exploration
We upload the collected data into Python and explore its features. This step involves visualizing the data to identify patterns and relationships between the different features and the target variable (stock return).
### 3. Data Cleaning
After exploring the data, the next task is to clean it. We handle missing values and ensure the dataset is ready for the next steps, including feature engineering and model training.
### 4. Feature Engineering
If necessary, new features are created to improve the model’s performance. This step may include deriving additional metrics or transforming existing features to better capture relevant information.
### 5. Training Machine Learning Models
Various machine learning models are applied to predict the return of the stock based on the available data. This includes model selection, training, and evaluation.
