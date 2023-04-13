In this example, I am using the Bitcoin Historical Data from Kaggle which can be found (https://www.kaggle.com/mczielinski/bitcoin-historical-data). The dataset contains minute-by-minute Bitcoin price data collected from Bitstamp.

### 0 - Meaning and use of each column for the business side

1. **Timestamp**: The timestamp for each minute of data.
2. **Open**: The opening price of BTC in USD at the beginning of the minute.
3. **High**: The highest price of BTC in USD during the minute.
4. **Low**: The lowest price of BTC in USD during the minute.
5. **Close**: The closing price of BTC in USD at the end of the minute.
6. **Volume_(BTC)**: The number of BTC traded during the minute.
7. **Volume_(Currency)**: The amount of USD traded during the minute.
8. **Weighted_Price**: The average price of BTC in USD during the minute, weighted by trading volume.



### 1 - State-of-the-art summary
 The dataset contains minute-by-minute historical price and trading volume data of Bitcoin against the US Dollar.
 In this analysis, we will resample the dataset to daily frequency and use the daily data for analysis and modeling.

### 2 - Dataset Description
 The resampled dataset consists of 8 columns representing timestamp, opening price, highest price, lowest price,
 closing price, trading volume in BTC, trading volume in USD, and weighted price.
