# LSTM-Stock-Predictor

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.


# Evaluation of Model Performance
1. Which model has a lower loss?

The model which uses the closing price has a lower loss than the model which uses the FNG index.

2. Which model tracks the actual values better over time?

The model using the closing price tracks the actual values better over time

3. Which window size works best for the model?

The FNG model isnt reliable to use as predictions, but using a 10 day window for the price data, it can kind of track the trend, but wouldnt reliably use it for price predictions.