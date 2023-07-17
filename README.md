# Covid-19 Time Series Analysis

## Overview
This repository contains code developed for my university project, focusing on the analysis of Covid-19 datasets using three different models for prediction. The project aims to compare the performance of three models: ARIMA, LSTM, and Decision Forest.

## Models Considered
The following models are utilized in this project:

### ARIMA (AutoRegressive Integrated Moving Average)
ARIMA is a widely used time series forecasting model that takes into account the autoregressive (AR), differencing (I), and moving average (MA) components. It is particularly useful for capturing patterns and trends in time-dependent data.

### LSTM (Long Short-Term Memory)
LSTM is a type of recurrent neural network (RNN) architecture that is effective in modeling and predicting sequences, making it suitable for time series analysis. Its unique memory cells allow it to retain information over longer periods, capturing both short-term and long-term dependencies in the data.

### Decision Forest
The Decision Forest model, also known as a Random Forest, is an ensemble learning method that combines multiple decision trees to make predictions. Each tree in the forest independently predicts the outcome, and the final prediction is determined by aggregating the individual tree predictions.

## Dataset
The project utilizes a Covid-19 dataset to train and evaluate the models. The dataset includes relevant variables such as date, confirmed cases, recovered cases, and deaths. By analyzing this dataset, I'm trying to make predictions about the future progression of the pandemic.

The dataset link: https://github.com/owid/covid-19-data

## Getting Started
To use this code, follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/ArtemDolgie/Covid-19-Time-series-analysis.git
   ```

## Results and Evaluation
After executing the code for each model, we will obtain predictions for the Covid-19 time series data. The results will be evaluated based on various performance metrics, such as accuracy, precision, recall, and F1 score, to assess the effectiveness of each model in predicting the future progression of the pandemic.

Feel free to explore the code, modify it according to your needs, and analyze different Covid-19 datasets using the provided models.

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or additional models to include, please submit a pull request or open an issue.
