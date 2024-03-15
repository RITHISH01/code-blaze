# Code Blaze

## Overview
In this analysis, we utilized the ARIMA model to forecast the values of Ethereum, Chainlink, and Arbitrum cryptocurrencies. ARIMA (AutoRegressive Integrated Moving Average) is a time series forecasting method that combines past values to make predictions.

We gathered the data from March 1st to March 15th to train and test our model. To evaluate the performance of our model, we employed Root Mean Square Error (RMSE).

Additionally, we utilized the pmdarima library to determine the best parameters (p, d, q) for our ARIMA model. PMD ARIMA models segment time series data into distinct intervals and fit separate ARIMA models to each segment, allowing for flexible modeling of non-stationary behavior.

## Requirements
- pandas
- pmdarima
- matplotlib
- scikit-learn

## Installation
To install the required packages, run the following command:
