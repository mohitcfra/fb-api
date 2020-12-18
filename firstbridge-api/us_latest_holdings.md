Returns the constituent holdings data for a given ETF.
The API returns 1000 constituent rows per page. The value "previous": false indicates it is the first page, and "next": false indicates it is the last page.

Request:
```
GET
/yt/v1.0/us/holdings/latest?ticker=bndw&page=16
```

Response:
```
{
    "count": 15442,
    "next": false,
    "previous": true,
    "results": [
        {
            "id": "7b0500bf-a9e9-448c-b9e1-55332fadd0b6",
            "firstbridge_id": "343800ae97934397aea2c8c057191bf2",
            "as_of_date": "2020-11-30",
            "constituent_name": "United States Treasury Note/Bond",
            "constituent_ticker": null,
            "location": "GR",
            "constituent_type": "BOND",
            "share_class_figi": null,
            "isin": "US912828H862",
            "sedol": "BVJF875",
            "iso_market_identifier_code": null,
            "sector": null,
            "industry": null,
            "sub_industry": null,
            "market_value_held": 171831.0,
            "market_value_currency": null,
            "market_value_local": null,
            "notional_value": null,
            "contract_expiry_date": null,
            "quantity_held": null,
            "quantity_per_share": null,
            "quantity_units": null,
            "weighting_sponsor": 0.0003592176,
            "weighting_inhouse": null,
            "face": 169135.0,
            "coupon": 1.5,
            "maturity": "2022-01-31",
            "local_price": null,
            "local_currency": null,
            "converted_price": null,
            "converted_currency": null,
            "currency_conversion_rate": null
        },
        {
            "id": "2a816bbf-0434-4e7f-ad29-fcf96ece138d",
            "firstbridge_id": "343800ae97934397aea2c8c057191bf2",
            "as_of_date": "2020-11-30",
            "constituent_name": "United States Treasury Note/Bond",
            "constituent_ticker": null,
            "location": "GR",
            "constituent_type": "BOND",
            "share_class_figi": null,
            "isin": "US9128283V09",
            "sedol": "BFMTY85",
            "iso_market_identifier_code": null,
            "sector": null,
            "industry": null,
            "sub_industry": null,
            "market_value_held": 171805.0,
            "market_value_currency": null,
            "market_value_local": null,
            "notional_value": null,
            "contract_expiry_date": null,
            "quantity_held": null,
            "quantity_per_share": null,
            "quantity_units": null,
            "weighting_sponsor": 0.0003591632,
            "weighting_inhouse": null,
            "face": 157394.0,
            "coupon": 2.5,
            "maturity": "2025-01-31",
            "local_price": null,
            "local_currency": null,
            "converted_price": null,
            "converted_currency": null,
            "currency_conversion_rate": null
        }
    ]
}
```