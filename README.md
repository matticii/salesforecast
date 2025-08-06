This notebook forecast the Year-over-year percent change in Brand Comparable Sales (also known as “Same Store Sales”) for Party City (NYSE: PRTY) for the period ending 12/31/2022, 3/31/2023, 6/30/2023, and 9/30/2023, using the provided transaction data and store location information.

A simple linear regression model was used and showed great accuracy in predicting brand comparable sales using 1% of each store's sales data. However, such store sales data may not often be available (we are assuming that after PRTY was delisted on January 18, 2023, the company is no longer required to report its performance publicly). In such cases where we do not have store sales data, we applied SARIMAX models to make use of the autoregressive nature of time series data for prediction.


