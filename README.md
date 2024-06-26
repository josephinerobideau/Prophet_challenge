# Challange 8 - Forecasting Google search trends for MercadoLibre
-------

## Overview and agenda for prophet traffic forecasting
1. Install and import libraries and dependencies
- Install
  - prophet
    - Used for forecasting future search traffic
- Import
  - pandas
    - Used for all data related tasks (ex. data manipulation)
  - datetime
    - Used for all data including a date and/or time
  - numpy
    - Used for working with arrays and matricies
  - matplotlib.pyplot
    - Used for creating visual plots
  - matplotlib inline
    - Used for direct, and easy interaction with visual plots
2. Find unusual patterns in Google's hourly search trends
- Read in, and view DataFrame
- View dtypes
- Slice data for only the month of May 2020, and plot visual
- Calculate the total search traffic for May 2020, and compare to the monthly median traffic for all months
  - Calculate the sum of May 2020 search trends
  - Calculate monthly median search traffic across all months
  - Compare
3. Mine the search traffic data
- Group the hourly search data to plot the average traffic by hour of the day
- Group the hourly search data to plot the average traffic by the day of the week (M-F)
- Group the hourly search data to plot the average traffic by the week of the year
4. Relate the search traffic to stock price patterns
- Read in and plot the stock price data
- Concat the stock price data to the search data by columns into one DataFrame
  - Plot merged DataFrame
  - Slice merged DF to 2020-01 through 2020-06, visualize data, and analyze data
- Create a new column for both stock volatility and hourly stock return, visualize data, and analyze data
- Review the time series correlation and predict possible relationship, if any
5. Create a time series model with prophet
- Set up Google search data for a prophet forecasting model
  - Clean DF, fit model, predict model
- Plot the forecast and infer possible future outcomes
- Plot the individual time series components and infer possible future outcomes
-------
### Additional sources
#### Sources like ChatGPT, Xpert learning assistant, AskBCS, Google, Youtube, and Columbia provided tutoring were used for clarification, and debugging if/where needed.
