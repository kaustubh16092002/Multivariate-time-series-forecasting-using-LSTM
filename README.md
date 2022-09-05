# Multivariate-time-series-forecasting-using-LSTM
I have taken the dataset from "https://finance.yahoo.com/quote/TSLA/history?p=TSLA"
Here since it is a multivariate time series approach multiple inputs are given as input for single day prediction of one day in the future, The input size is (n, 14, 5) where 14 was the number of days we look back and 5 was the number of variables. It only has multiple variables available until the last day in our input. So it will predict one day into the future.

