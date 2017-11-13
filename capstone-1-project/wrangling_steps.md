# Data Wrangling steps.

## Wrangling

- The bitcoin and litecoin data were obtained using the open source cryptocompare python library.

- The Google search term trend data was obtained using the python library, pytrends.

## Cleaning

- The data was fairly clean as it is coming from two very reputable sources (Google and Coinbase).

- The Google search trend data is returned by week and the coin data is by day.  Therefore, the Google search trend data is interpolated between weeks to obtain a daily value.

- Bitcoin is much older than litecoin.  Therefore, there is more price history for bitcoin than there is for litecoin.  Due to this, the bitcoin historical data that exists before there was any litecoin data was discarded.  This was not necessary but this project will focus on more recent years and therefore would not be using the discarded data anyway.

- There appear to be no outliers so there was nothing to be done there.
