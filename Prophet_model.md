I did a Facebook Prophet model for stock prices. The code takes three stocks and analyzes the data to predict 90 days into the future.

First, we get ticker data, validate the ticker symbol and create a dataframe for each symbol. In the example we used MSFT, GOOG, and TSLA.

Next, we create a list of tickers and loop through them. We then create a forecast dataframe that goes out 90 days.

We plot historical and future data.

![three_stock_plot](/images/three_stock_plot.png)

We determine Best Case, Worst Case and Most Likely Case for each symbol. In our example going out 90 days, MSFT has a Best Case of 271.81, a Worst Case of 249.01 and a Most Likely Case of 260.05. GOOG has a Best Case of 1943.35, a Worst Case of 1741.48, and a Most Likely Case of 1843.42. TSLA has a Best Case of 887.23, a Worst Case of 419.52, and a Most Likely Case of 646.46.

![msft_forecast](/Desktop/msft_forecast.png)

![goog_forecast](/Desktop/goog_forecast.png)

![tsla_forecast](/Desktop/tsla_forecast.png)






