This document will go over methodology and sources for corrected version

The data inputs folder has four excel spreadsheets in it which have the following data: year-dividends per share, day-S&P 500
closing price(dec 31), year-December CPI, and complete S&P 500 closing price data for every day going back to 1927.

The data for dividends per share taken from your website.

The data for dec CPI on any given year was gathered by downloading historical monthly CPI-U from The U.S. Bureau of Labor 
Statistics. The target data was then isolated in excel. Source(https://data.bls.gov/timeseries/CUUR0000SA0?years_option=all_years)

The data for S&P 500 closing prices was gathered from yahoo finance. The dec 31 data was then isolated in excel.
Source(https://finance.yahoo.com/quote/%5EGSPC/history/)

NOTE: the dec 31 data is labeled as Dec31S&Pdata.xlsx and the full closing price dataset is labeled S&PClosingPriceFullData.xlsx

NOTE: I know you didn't ask for the full closing price history but I figured it would be useful to you at some point in the future 
given what you do.

In the code the nominal and real returns where calculated with the formula given.

The charts are located in the chart folder and include a QQPlot, ACFPlot, and an estimated density function for both nominal and real returns.

In the folder code you will find a PDF of the code used to make the final spreadsheet and make the charts