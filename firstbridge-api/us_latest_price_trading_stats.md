Returns the latest available prices and price-based returns for a specified composite_ticker.  

Request:
```
GET 
/yt/v1.0/us/price_trading_stats/latest?ticker=spy
```

Response:
```
{
    "beta_vs_spy": 1.0,
    "split_only_ytd_return": 0.13297707077611376,
    "split_and_dividend_ytd_return": 0.14923577556853984,
    "return_split_only_one_month": 0.03241697573681401,
    "return_split_and_dividend_one_month": 0.03241697573681401,
    "return_split_only_three_month": 0.07199341505717727,
    "return_split_and_dividend_three_month": 0.07628528852101013,
    "return_split_only_one_year": 0.1491869406277575,
    "return_split_and_dividend_one_year": 0.1714093357825044,
    "annualized_return_split_only_three_year": 0.10980059454560731,
    "annualized_return_split_and_dividend_three_year": 0.13105805218897704,
    "annualized_return_split_only_five_year": 0.12553490101659248,
    "annualized_return_split_and_dividend_five_year": 0.14787119577662478,
    "annualized_return_split_only_ten_year": 0.11411695288899804,
    "annualized_return_split_and_dividend_ten_year": 0.13662705101385164,
    "annualized_return_split_only_inception": 0.07893237530175612,
    "annualized_return_split_and_dividend_inception": 0.09931412517785332,
    "return_split_only_5_year_prior": -0.008124939184586899,
    "return_split_and_dividend_5_year_prior": 0.012343873980927622,
    "return_split_only_4_year_prior": 0.09643400206013641,
    "return_split_and_dividend_4_year_prior": 0.11997914219508465,
    "return_split_only_3_year_prior": 0.19384422672571922,
    "return_split_and_dividend_3_year_prior": 0.21705457649036508,
    "return_split_only_2_year_prior": -0.06347897774113775,
    "return_split_and_dividend_2_year_prior": -0.045691819403488876,
    "return_split_only_1_year_prior": 0.2878521126760565,
    "return_split_and_dividend_1_year_prior": 0.3122359498705145,
    "average_daily_volume_one_month": 60920629.0,
    "average_daily_volume_three_month": 73533734.953125,
    "average_daily_volume_six_month": 72755468.88976377,
    "volatility_annualized_one_year": 0.3353908679382335,
    "volatility_annualized_three_year": 0.2289792557466307,
    "volatility_annualized_five_year": 0.19004816542159128,
    "split_only_daily_return": -0.004477204477204455,
    "split_and_dividend_daily_return": -0.004477204477204455,
    "as_of_date": "2020-12-14",
    "open_price_unadjusted": null,
    "high_price_unadjusted": null,
    "low_price_unadjusted": null,
    "close_price_unadjusted": null,
    "open_price_split_adjusted": 368.64,
    "high_price_split_adjusted": 369.8,
    "low_price_split_adjusted": 364.47,
    "close_price_split_adjusted": 364.66,
    "open_price_split_dividend_adjusted": 368.64,
    "high_price_split_dividend_adjusted": 369.8,
    "low_price_split_dividend_adjusted": 364.47,
    "close_price_split_dividend_adjusted": 364.66,
    "market_capitalization": 313929272420.56,
    "volume_traded": 69216174.0,
    "high_unadjusted_52_week": null,
    "low_unadjusted_52_week": null,
    "high_split_adjusted_52_week": 369.8,
    "low_split_adjusted_52_week": 364.47,
    "high_split_dividend_adjusted_52_week": 369.8,
    "low_split_dividend_adjusted_52_week": 364.47,
    "firstbridge_id": "34899d2ddd104e50bc16b57db56b2eec"
}
```
