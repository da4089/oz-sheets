# asx-sheets

Fetch stock market data for ASX codes into Google Sheeets.

This provides ASX functions in Apps Script for Google Sheets,
the original idea of which came from
[a reddit post](https://www.reddit.com/r/ASX_Bets/comments/mbbdvf/how_to_get_3_decimal_places_for_stock_prices_in/)

## Functions

```ASX_last_price(symbol)``` will fetch the current (but 30m delayed) price from the ASX website

```ASX(symbol, attribute)``` will return the value of any attribute for a given symbol from the ASX website.

Currently supported attributes are:
```
annual_dividend_yield
average_daily_volume
bid_price
change_in_percent
change_price
code
day_high_price
day_low_price
deprecated_market_cap
deprecated_number_of_shares
desc_full
eps
isin_code
last_price
last_trade_date
market_cap
number_of_shares
offer_price
open_price
pe
previous_close_price
previous_day_percentage_change
suspended
volume
year_change_in_percentage
year_change_price
year_high_date
year_high_price
year_low_date
year_low_price
year_open_date
year_open_price
```
