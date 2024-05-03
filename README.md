# Machine_Learning_Project

This project aims to develop and evaluate machine learning models for predicting stock price movements based on technical indicators. It encompasses various stages including data retrieval, preprocessing, exploratory data analysis, model specification, testing, and evaluation.

## Programs and programming languages
- Python

## Data Retrieval
For the project I utilized price and trading indicators 10 bluechip company stocks from S&P 500 representing different industries. The base data which includes daily opening and closing prices, daily high and lows and volume are retrieved from Yahoo Finance API. Using the trading data I calculated 93 various technical indicators, which indicate the volume, volatility, trend, momentum and other technical features of stock price.

## Exploratory Data Analysis
The project includes extensive exploratory data analysis, including:
- Stock Price series trend analysis
- Trading volume analysis
- Return on price analysis

## Model Selection
The project employs the following Machine Learning models:
- Lasso regression
- Random Forest regression
- Gradient Boosting regression
- Elastic Net regression


After selecting the model, I conducted hyperparameter tuning by testing the model on a validation dataset to optimize the parameters. Subsequently, the final models were trained on the existing dataset and utilized for prediction purposes.

## Results
The project's main findings include:
- Prediction of Stock prices using its technical indicators 
- Evaluation of Machine learning regression models  
  
## Files Included
- `README.md`: This file provides an overview of the project.
- `CS 671. Final project-final.ipynb`: Python script containing the entire project code.
