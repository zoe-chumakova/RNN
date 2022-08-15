# RNN
Predicting stock price movement using RNN

The goal of this exercise is to predict the upward and downward trends for Tesla stock (data source : https://finance.yahoo.com/)
The model implemented is LSTM (last short-term memory). LSTM wwas trained on 5 years of Tesla stock price in order to predict the first month of January 2022 trend.
Train data: 1258 records (01.03.20117 to 12/30/2021)
Test data: 20 records (01.03.2022 to 01.31.2022)

Steps:
	1) Stock Data Preprocessing: importing libraries and training data, scaling and reshaping.	
	2) Building RNN: RNN initializing, adding 4 LSTM layer and Dropout regularization, adding output layer, RNN compiling (Adam optimizer and MSE loss function) and fiitting RNN to the training set.	
	3) Predictions and visualization: predict test stock prices based on RNN model and visualising real test data vs predicted test data.

Credit: tfcertification.com
