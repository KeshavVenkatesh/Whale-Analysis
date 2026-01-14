# Whale-Analysis

Here are descriptions of each of the csv files, which include their column names and what they represent:

**[btc_and_eth_returns.csv](https://github.com/KeshavVenkatesh/Whale-Analysis/blob/main/btc_and_eth_returns.csv)**

Contains the following (relevant) columns:
- **Date**: The date for which the data is being calculated.
- **Average Price**: The average of the prices of BTC and ETH for this date.
- **Weighted Price**: A weighted average of the prices of BTC and ETH for this date (weighted by market cap).
- **Average Return**: The average of the returns (Today's Price - Yesterday's Price) of BTC and ETH for this date.
- **Weighted Return**: A weighted average of the returns of BTC and ETH for this date (weighted by market cap).
- **Average Return Growth**: The average of the return growths ((Today's Price - Yesterday's Price) / Yesterday's Price) of BTC and ETH for this date.
- **Weighted Return Growth**: A weighted average of the return growths of BTC and ETH for this date (weighted by market cap).

**[btc_market_cap.csv](https://github.com/KeshavVenkatesh/Whale-Analysis/blob/main/btc_market_cap.csv)**

Contains the following (relevant) columns:
- **snapped_at**: The date for which the data is being calculated.
- **market_cap**: The market cap of BTC for this date.

**[eth_market_cap.csv](https://github.com/KeshavVenkatesh/Whale-Analysis/blob/main/eth_market_cap.csv)**

Contains the following (relevant) columns:
- **snapped_at**: The date for which the data is being calculated.
- **market_cap**: The market cap of ETH for this date.

**[ethereum_price.csv](https://github.com/KeshavVenkatesh/Whale-Analysis/blob/main/eth_market_cap.csv)**

Contains the following (relevant) columns:
- **Date**: The date for which the data is being calculated.
- **Price**: The price of ETH for this date.

**[panel_regression_date.csv](https://github.com/KeshavVenkatesh/Whale-Analysis/blob/main/panel_regression_date.csv)**

Contains the following (relevant) columns:
- **Token**: The token for which the data is being calculated.
- **Date**: The date for which the data is being calculated.
- **Return Growth**: The return growth of the token for this date.
- **Whale Buy**: The number of whales who bought this token on this date.
- **Whale Sell**: The number of whales who sold this token on this date.
- **Market Cap**: The market cap of the token for this date.
- **Trading Volume**: The amount of the token that was transacted on this date.
- **Token_Age**: The lifetime of the token (in days).
- **Weighted Market Returns**: A weighted average of the return growths of BTC and ETH for this date (weighted by market cap).
- **Volatility**: A measure of how volatile the price of this token is (from 0 to 1).
- **Whale Size**: A percentage of the amount of this token owned by whales.
- **Whale Transaction Size**: A percentage of the amount of the transactions of the token on this date performed by whales.

**[panel_regression_date_whales.csv](https://github.com/KeshavVenkatesh/Whale-Analysis/blob/main/panel_regression_date_whales.csv)**

- Same as [panel_regression_date.csv](https://github.com/KeshavVenkatesh/Whale-Analysis/blob/main/panel_regression_date.csv), but only for whales and transactions performed by whales.

**[tokens.txt](https://github.com/KeshavVenkatesh/Whale-Analysis/blob/main/tokens.txt)**

- A text file of a list of 6,111 tokens.

**[whales.txt](https://github.com/KeshavVenkatesh/Whale-Analysis/blob/main/whalers.txt)**

- A text file of a list of 15,889 users who are whales of at least one token.
