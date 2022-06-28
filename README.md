# Stock Price Prediction using Machine Learning Algorithms

## Introduction
There are lots of people involved every day in trading stock, and hundred million dollars cash flow in these markets such as Nasdaq, New York Stock Exchange, Dow, S&P 500. Everybody would like to predict the stock price and get the benefit of the stock market. In this project, we will try to predict the direction of the given stock.

## Project Definition

### Project Overview

In this project, we will explore if machine learning algorithms can lead us to predict the direction of a given stock. For that reason, we pull up a dataset from yahoo finance for the stock and pre-process the data. After that, the data is examined with exploratory data analysis methods to check out whether historically performs well or not. Lastly, the project forecasts the stock price by applying various machine learning algorithms and compares the results.

### Problem Statement

The goal of the project is to predict price change and the direction of the stock using various machine learning models. Since the input(Adj Close Price) used in the prediction of stock prices are continuous values, we use regression models to forecast future prices. The list of tasks is involved as follow

1. Load historical stock price data from Yahoo Finance.
2. Check for missing values and data cleaning.
3. Process Exploratory Data Analysis.
4. Perform data preparation and feature engineering for machine learning.
5. Train the regression models.
6. Validate the models.
7. Select the best model and make a recommendation.

The best model will recommend the best stock price prediction for the investors.

## Metrics

For the project, we use *Root Mean Square Error* and *R2 score* to assess and validate the various machine learning algorithms.

The first one is, Root Mean Square Error (RMSE) is the standard deviation of the residuals. RMSE measures the error rate. It is easy to use in statistics. The formula is used as follow

$$\text{RMSE} = \sqrt{\sum_{i = 1}^{n}\dfrac{\left(\hat{y}_i - y_i\right)^2}{n}}$$

R-squared is a goodness-of-fit measure for regression models in statistics. The percentage of the independent variable explains that dependent variable. R-squared measures the strength of the relationship between your model and the dependent variable on 0–100% scale. If the relationship is strong, the scale is high otherwise, it is low.

In short, historical data of given stock is used to build a machine learning model and two metrics are applied to these models to select the best solution model. So, The project is based on selecting the model which has a low RMSE and high R2 Score value.

> The main work of the project is available at [this notebook](./src/Stock%20Prediction%20Using%20Machine%20Learning%20Algorithms.ipynb)