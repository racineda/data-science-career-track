# Capstone Project 1: Milestone Report

## Questions:

### Define the problem:
- The problem is predicting the price of bitcoin and/or litecoin from a known dataset.

### Identify your client:
- The client is any cryptocurrency investor.

### Describe your data set, and how you cleaned/wrangled it.
- The dataset is a combination of two sources.  The first source is Coinbase, which is a cryptocurrency exchange.  From this source, the historical price data can be obtained for the cryptocurrencies of interest.  The second dataset comes directly from Google trends.  This source has the ability to provide the frequency a particular search term is used on Google.  This is provided by week but needs to be by day so it is resampled by day and interpolated to obtain a daily estimate.

### List other potential data sets you could use.
- There are many different cryptocurrency exchanges such as Bitstamp that could serve as a replacement for Coinbase.  There, really is no substitute for Google.  It is by far the largest search engine in the world.  Google is currently blocked in China so it is not represented.  However, since cryptocurrency trading has been banned in China, the data there is largely irrelevant.

### Explain your initial findings.
- The initial findings seem to suggest a positive correlation between the closing price of the cryptocurrency and the frequency of the Google search trend.
