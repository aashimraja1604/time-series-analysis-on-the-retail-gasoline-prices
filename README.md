# time-series-analysis-on-the-retail-gasoline-prices
![image](https://user-images.githubusercontent.com/78611284/216685873-9042acbe-8bce-4b0d-8ea9-635381ea9b51.png)
- The code is performing a time series analysis on the retail gasoline prices data obtained from the Energy Information Administration (EIA) website. 
- It downloads the data as a pandas dataframe, preprocesses it, normalizes it using StandardScaler, and then trains a LSTM model on 96% of the data and tests it on the remaining 4%. 
- The code calculates the mean squared error between the actual prices and the prices predicted by the model and outputs the root mean squared error. 
- Finally, it creates a combined list of the predicted prices from both the training and the test sets and plots the actual and predicted prices.
