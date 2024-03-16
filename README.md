# Time-Series-Forecasting-of-DJIA-Using-SARIMAX-and-LSTM-Models

This repository contains code and analysis for predicting the future values of the Dow Jones Industrial Average (DJIA) using two different time-series forecasting models: **SARIMAX** and **LSTM**.

## Project Overview

The DJIA represents a broad cross-section of large U.S. companies, making it an attractive index for investors. However, with the tech industry's dominance, understanding its behavior has become more critical than ever. In this project, we explore how well SARIMAX and LSTM models can predict DJIA values.

## Data

We use historical DJIA value daily data from 1885 to 2024. The dataset includes daily closing prices, which we'll use to train and evaluate our models.

## Models

1. **SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors)**:
   - SARIMAX is a powerful statistical model that combines autoregressive (AR), moving average (MA), and seasonal components.
   - We fit the SARIMAX model to the DJIA data and evaluate its performance.
   - Confidence intervals for the predictions are calculated to assess accuracy.

2. **LSTM (Long Short-Term Memory)**:
   - LSTM is a type of recurrent neural network (RNN) that excels at capturing long-term dependencies in time-series data.
   - We build an LSTM model to predict DJIA values.
   - LSTM outperforms SARIMAX in terms of accuracy.

## Results

- The SARIMAX model provides reasonable forecasts on train dataset, but it's accuracy on validation and test dataset is't acceptable .
- LSTM, on the other hand, predicts DJIA valuess more accurately.
- We visualize the predictions and compare them to the actual values for test dataset.
