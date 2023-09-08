Airflow-coingecko
-Use API from this web "https://www.coingecko.com/" to get exchange rate with USD for top 8 coins on Coingecko.
+ use DB MySQL to:
- Get information of 8 coins: description in Eng language, symbol, all time high(ath), all time low(atl), ath date,
atl date, homepage, genesis date (ngày phát hành) to table: "basic_infomation".
- Extract historical data from 1 year day by day(from 24/3/2022) to table: 'all_historical_data_coin'.
- Calculate mean, max, min for each coin in 1 month, 6 months, 1 year ago, year 2022 and load into another 
table: 'statistics'.
