# Stock-Market-Forecasting
## Details about the Project
For Stock Market Forecasting I have used different forecasting models like Auto ARIMA, LSTM(Long Short-Term Memory Networks) and Linear Regression. Autoregressive integrated moving average, or Auto 
ARIMA, is a form of quantitative method that involves time-series data to better comprehend a data set or forecast future events. The Long and Short Term Memory architecture is It is a 
supervised neural architecture that is built on artificial recurrent neural networks (RNN). A technique for estimating the value of one variable in terms of another is linear regression 
analysis.
## Dataset
The data collected for the experiment consists of the daily opening prices, closing prices, low, high, adjacent low, adjacent high, volume of a stock in the New York Stock Exchange 
NYSE(NSRGY) extracted from Tiingo, for NSRGY out data series cover the period from previous 5 years for example the data from 13/05/2017 to 13/05/2022 is considered. To build this 
model LSTM, Auto Arima, Linear Regression and KNN are used. 60 percent of the existing data is used for training, while the residual 40% is used for testing in each of these models. During 
training, we use mean square error to improve our model.
## Results
| Models | Root Mean Square | Mean Square | Mean Absolute Error | 
|--------|------------------|-------------|---------------------|
| KNN    | 30.90 | 955.28 | 30.07 | 
|Linear Regression  | 6.36 | 40.8 | 5.26|
| Auto Arima | 23.98 | 575.34 |  20.95 |
| LSTM | 2.19 | 4.81 | 1.70|
