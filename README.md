# CoinSeeker
CoinSeeker is a python program that helps track various cryptocurrency coins from coinmarketcap.com's API
## Instructions
- Run the 'API Caller' to generate a new .csv file
- 'API Caller' will fetch new data after a certain delay (can be configured)
- Once you have the desired data, 'API Analysis' file can be used
- 'API Analysis' fetches the data from .csv file and displays two types of charts

### Analysis #1
- Tells the user about percentage increase/decrease of a crypto coin over a period of time
- Provides a categorical point plot to compare all the crypto coins at once

![categorical point plot of percentage increase of cryptocurrencies over a timeframe](https://i.postimg.cc/CMJP6Xw4/Screenshot-2025-10-15-075710.png)

### Analysis #2
- Shows the price history of all crypto coins that are specified in the 'coin_type' python list\
- Plots line graphs for each of the crypto coins

![line plot to showcase the price history of each crypto coin](https://i.postimg.cc/wB7RgtNy/Screenshot-2025-10-15-080413.png)
