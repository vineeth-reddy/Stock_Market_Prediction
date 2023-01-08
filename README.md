# Stock_Market_Prediction

In this notebook, I'll be analyzing stock market data of 6 top companies (Netflix, Apple, Amazon, Google, Meta and Tesla). I'll use yfinance to get stock information, and visualize different aspects of it using Seaborn and Matplotlib and also look at a few ways of analyzing the risk of a stock, based on its previous performance history. I'll also be predicting future stock prices through a Long Short Term Memory (LSTM) method!

<h3>Getting the Data</h3>

The first step is to get the data and load it to memory. We will get our stock data from the Yahoo Finance website. Yahoo Finance is a rich resource of financial market data and tools to find compelling investments. To get the data from Yahoo Finance, we will be using yfinance library which offers a threaded and Pythonic way to download market data from Yahoo. Check this article to learn more about yfinance: Reliably download historical market data from with Python

<h3>1. What was the change in price of the stock overtime?</h3>

In this section I'll be performaning some analysis of stocks using pandas, and analyze basic attributes of a stock.

<h3> 2. What was the moving average of the various stocks? </h3>

The moving average (MA) is a simple technical analysis tool that smooths out price data by creating a constantly updated average price. The average is taken over a specific period of time, like 10 days, 20 minutes, 30 weeks, or any time period the trader chooses.

<h3>3. What was the daily return of the stock on average?</h3>

 We're now going to analyze the risk of the stock. In order to do so we'll need to take a closer look at the daily changes of the stock, and not just its absolute value.
 
 <h3>4. What was the correlation between different stocks closing prices?</h3>
 
 In this section, We'll explore correlation between various stocks.
 
 <h3> 5. How much value do we put at risk by investing in a particular stock?  </h3>

There are many ways we can quantify risk, one of the most basic ways using the information we've gathered on daily percentage returns is by comparing the expected return with the standard deviation of the daily returns.

<h3>6. Predicting the closing price stock price of GOOGLE inc:</h3>

We'll build an LSTM model to predict the future stock prices.
