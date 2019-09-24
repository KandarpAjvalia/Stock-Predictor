A program to predict stock prices for any stock using SVM (Support Vector Machine), a Regressor,
and using Linear Regression.

To use:
	1. Register on Quandl and get the API Key.
	2. Put the Quandl API Key in the line: 
		quandl.ApiConfig.api_key = '#PUT THE QUANDL API KEY HERE'
	3. To predit the price a stock, change line and replace with any ticker of your choice:
		We have AMZN: Amazon, so replace AMZN with any ticker of your choice
		df = quandl.get("WIKI/AMZN")
	     eg.df = quandl.get("WIKI/JPM") 
	4. Can change the number of days of stock that is predicted by changing "n", currently n is set
	   to 30, meaning the program will predict 30 days of stock.
	5. The program also shows the accuracy levels (R^2) for svm and linear regression
