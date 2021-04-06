# Finance-Data-Project-Stock-Prices-Using-Python
1. The Finance data project is focused on exploratory data analysis and visualization of stock prices.  
2. This project is basically made for to use of the libraries like Numpy, Pandas, matplotlib, seaborn,plotly and cufflinks.


# LIBRARY REQUIREMENTS 
1. Pandas DataReader
2. Numpy
3. Pandas
4. Datetime
5. Seaborn
6. Matplotlib
7. Plotly
8. Cufflinks

# Dataset
1. The data is about Bank Stocks and related to the financial crisis to the early 2016. 

# Figure Out
1. Need to figure out how to get the stock data from Jan 1st 2006 to Jan 1st 2016 for each of this banks.

So, First we need to set each bank to the seprate dataframe, with the variable name for that bank being its ticker symbol. This will involve a few steps:
   1. Use datetime to start and end datetime objects.
   2. Figure out the ticker symbol for each bank.
   3. Figure out how to use datareader to grab info on the stock.

# Questions to work on

1. Create a list of the ticker symbols (as strings) in alphabetical order. call list as tickers
2. Use pd.concat to concatenate the bank dataframes together to a single data frame called bank_stocks. Set the keys argument equal to the tickers list. Also pay attention to what axis you concatenate on.
3. Set the column name levels
4. Check Some Exploratory Data Analysis. What as the max Close price for each bank's stock throughout the time period?
5. Create a new empty DataFrame called returns. This dataframe will contain the returns for each bank's stock.
6. We can use pandas pct_change() method on the Close column to create a column representing this return value. Create a for loop that goes and for each Bank Stock Ticker creates this returns column and sets it as a column in the returns DataFrame
7. Create a Pairplot using seaborn of the return dataframe. What Stocks stands for you?
8. Using this returns DataFrame, figure out on what dates each bank stock had the best and worst single day returns. you should notice that 4 of the share the same day for the worst drop, did anything significant happen that day?
9. To find out standard deviation of the returns, Which stock would you classify as the riskiest over the entire time period? which would you classify as the riskiest for the year 2015?
10. Create a distplot using seaborn of the 2015 returns for Morgan Stanley
11. Create a distplot using seaborn of the 2008 returns for the CitiGroup
12. Create a line plot showing Close price for each bank for the entire index of time.
13. Moving Averages:-  
                     1.Lets analyze the moving averages for these stocks in the year 2008
                     2.Plot the rolling 30 days average agaianst the close price for Bank's of Americas stocks for the year 2008.  

14. Create a heatmap of the correlation between the stocks Close price
15. Use Seaborn's clustermap to cluster the correlations together
16. Create Technical analysis plots using cufflinks
17. Use .iplot(kind='candle') to create a candle plot of Bank's of America's stock from Jan 1st 2015 to 1st Jan 2016
18. Use .ta_plot(kind='sme') to create a simple moving Averages plot of Morgan Stanley for the year 2015.


