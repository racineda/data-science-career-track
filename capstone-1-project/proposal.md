# Capstone 1 - Project Proposal

## The Question: 
- How closely do bitcoin and litecoin follow their respective Google keyword searches?

## The Data:
### Bitcoin & Litecoin:
-   Price data will be taken from coinbase(https://www.coinbase.com/) using its backend API.
    - There is a library(cryCompare) for python that allows for easy import into a script here: https://github.com/stefs304/cryCompare

  - Trading volume data will be taken from here: https://data.bitcoinity.org/markets/volume/all?c=c&exchange=coinbase&r=day&t=b

### Google search terms:
- The Google keyword trends will be pulled from, Google Trends (https://trends.google.com/trends/), using pytrends.

## Analysis:
- The trading volume and change in share price financial indications will be evaluated in this project.

## Summary:
- The project will progress through several different stages:

    - Data Wrangling: The data needs to be obtained and stored in memory within a python script.  There will be a few different data sources that will either need to be downloaded or obtained directly from the web at the time of execution.

    - Data Cleaning: The data should be fairly clean.  It will require aggregating the data into a single data frame for easier analysis.

    - Exploratory Data Analysis: The data will be visualized and interesting trends will be investigated further.

    - Inferential Statistical Analysis: A full statistical analysis will be completed to allow the project question to be answered.
