# portfolio_optimization
Portfolio Optimization capstone project 


Notebooks structure:

1) Step 1: Database consolidation v03

•Databases ensemble: 1) S&P500 Index, 2)Dow Jones Ind, 3)Interest Rates, 4)Spread, 5)Inflation, 6) VIX, 7) S&P500 stocks
•Additionally, some Feature Engineering and data preparation/cleaning
•Result: Database and Database(alldays)


2) Step 2: Model Selection v03

•Models tested: 1)SKLearn Linear Regression, 2)SARIMAX, 3)Prophet, 4) Vector Autoregressive, 5) NN, 6) LSTM, 7) Merlion, 8)Darts
•Result: Darts was the model chosen


————————————————————————————————————————————————————————————————————————————
After completing the initial step, we proceeded to iterate through each year individually, covering the years 2019, 2020, 2021, and 2022. To ensure a systematic and coherent analysis, it was crucial to use the notebooks corresponding to each specific year in a consecutive sequence, starting from the beginning and progressing through the end, before moving on to the subsequent year's analysis. By following this approach, we maintained a consistent framework throughout the evaluation, enabling us to effectively compare and comprehend the portfolio's performance over the course of multiple years.
————————————————————————————————————————————————————————————————————————————


3) Step 3: Assets Forecast v04 (YYYY)

•Forecast of the 500 stocks in the S&P500
•Result: Historical.csv (2 years) and Forecast.csv (2 years of historical + 1 year of projections)


4) Step 4: Assets Selection v02 (YYYY)

• By using the SLSQP optimizer: Selection of a combination of 30 stocks with that generates the highest Sharpe Ratio 
•Result: Selected_Stocks(Forecast).csv and Selected_Stock(Historical).csv 


5) Step 5: Portfolio Evaluation v02 (YYYY)

•Assuming we have invested $1,000 in the recommended portfolio, analyze the performance for the year 2019, 2020, 2021, and 2022.
•Result: Return and Volatility for the Forecast Portfolio, Historical Portfolio, Max_Stock Forecast, Max_Stock Historical, S&P500 Index.
