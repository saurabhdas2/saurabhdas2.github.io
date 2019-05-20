---
title: "Predictive Analytics –  Using Deep Learning Techniques"
categories:
  - Blog
tags:
  - AI
  - deep learning
  - time-series
  - predictive analytics
---

A good performance monitoring method, should understand the current and past trends, and based on that should be able to predict the future scores.
Time series model is purely dependent on the idea that past behavior and patterns can be used to predict future price behavior.

Deep Learning methods, such as **Recurrent neural nets(RNN)**, **Long Short-Term Memory(LSTM)**, offers a lot of promise for _Time Series forecasting_, such as the automatic learning of temporal dependence and the automatic handling of temporal structures like trends and seasonality.

Recurrent neural nets(RNN) are a type of artificial neural network designed to recognize patterns in sequences of data, such as 
1. Text Eg. Handwriting, genome code sequences.
2. Number Eg. Times series data emanating from sensors, stock markets 

**Long Short-Term Memory (LSTM)** networks are a type of recurrent neural network capable of learning order dependence in sequence prediction problems. Recently, there has been high emphasis on usage of LSTM for predicting 

### Methodology used for LSTM in Clinical Trial data
* Calculated the key performance parameters for sites.
* Transformed the time series data to supervised learning model
* Transformed the dataset to stationary, to take care of trends, seasonality etc .
* Scaled the model, to conform to neural network training.
* Created the model, with the training sample, and used it to predict the next time series.
* The final network had a visible layer with 1 input, a hidden layer with 4 LSTM blocks or neurons, and an output layer that makes a single value prediction. The network is trained for 3000 epochs and a batch size of 1 is used. RMSE was within range of 0.011 – 1.491.

