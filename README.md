
# Stock-Movement-Prediction-CNN

## Introduction:
Multivariate time series data are ubiquitous in many practical applications ranging from health care, geoscience, astronomy, to biology and others.

In this project, I  trained a convolutional neural network to take in an image of a graph of time series data for past prices of a given assets and then predict the movement of the price in the next day. 

WorkFlow: 
1. Obtain the data from several stocks, 
2. Plot closing price and volume  for given window of time for each of the stocks and stitch them to together. For example: 
    for example image at Ta with given window of 20 includes previous 20 closing prices for all of the requested stocks.
3. Label: the label indicate if the price moved 2% higher from previous day. for example if the price go 2% higher the next day, lable       will be 1, otherwise, 0 



