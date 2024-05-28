# EAD0830-time-series-forecasts
Basically, in the first part of the code, I analyze what type of time series we have, semiannual and quarterly, deseasonalized and normalized. 
In the second part of the code, I use an ML model, LSTM, where the series are normalized. I create a loop for the number of past observations I will use as a reference, apply the LSTM to train the model with the hyperparameters, make predictions, and invert the normalization.
