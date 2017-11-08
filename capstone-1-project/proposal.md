# Capstone 1 - Project Proposal

## The Question: How closely does bitcoin follow the S&P 500 index, gold,
                 litecoin, oil, U.S. unemployment rate, and inflation.

## The Data:
### Bitcoin & Litecoin:
-   Price data will be taken from coinbase(https://www.coinbase.com/)
    using its backend API.
    - There is a library(cryCompare) for python that allows for easy import
      into a script here: https://github.com/stefs304/cryCompare

  - Trading volume data will be taken from here:
https://data.bitcoinity.org/markets/volume/all?c=c&exchange=coinbase&r=day&t=b

### S&P 500, Oil, Gold:
- S&P 500, Oil, Gold will be obtained from Yahoo finance at:
  https://finance.yahoo.com/quote/%5EGSPC/history?p=%5EGSPC,
  https://finance.yahoo.com/quote/CL%3DF?p=CL%3DF,
  https://finance.yahoo.com/quote/GC%3DF?p=GC%3DF respectively.
    * The data is in csv format and will require reading and merging.

### Inflation & Employment:
- Inflation and Unemployment data will be obtained from:
  https://data.bls.gov/timeseries/LNS14000000,
  https://beta.bls.gov/dataViewer/view/timeseries/LNS14000000 respectively.
  * The data is in excel format and will require reading and merging.
  * A linear interpolation will be used between months.

## Analysis:
- The trading volume and change in share price financial indications will be
  evaluated in this project.

## Summary:
- The project will progress through several different stages:

    - Data Wrangling: The data needs to be obtained and stored in memory
                      within a python script.  There will be a few different
                      data sources that will either need to be downloaded or
                      obtained directly from the web at the time of execution.

    - Data Cleaning: The data should be fairly clean.  It will require
                     aggregating the data into a single data frame for easier
                     analysis.

    - Exploratory Data Analysis: The data will be visualized and interesting
                                 trends will be investigated further.

    - Inferential Statistical Analysis: A full statistical analysis will be
                                        completed to allow the project question
                                        to be answered.
