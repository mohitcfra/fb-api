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
            "id": "3f863776-cba0-4275-a2c7-c50f7f7516a3",
            "firstbridge_id": "343800ae97934397aea2c8c057191bf2",
            "as_of_date": "2020-11-30",
            "constituent_name": "BMW Vehicle Owner Trust 2018A",
            "constituent_ticker": null,
            "location": null,
            "constituent_type": "BOND",
            "share_class_figi": null,
            "cusip": "09659QAE7",
            "isin": "US09659QAE70",
            "sedol": null,
            "iso_market_identifier_code": null,
            "market_value_held": 1389.0,
            "notional_value": null,
            "contract_expiry_date": null,
            "quantity_held": null,
            "weighting_sponsor": 2.9037e-06,
            "face": 1368.0,
            "coupon": 2.51,
            "maturity": "2024-06-25",
            "created_at": "2020-12-19T14:20:52.342197Z",
            "updated_at": "2020-12-19T14:20:52.342243Z"
        },
        {
            "id": "b86b5737-ad48-45cd-b4ec-dba336483b78",
            "firstbridge_id": "343800ae97934397aea2c8c057191bf2",
            "as_of_date": "2020-11-30",
            "constituent_name": "FHLMC Multifamily Structured Pass Through Certificates K087",
            "constituent_ticker": null,
            "location": null,
            "constituent_type": "BOND",
            "share_class_figi": null,
            "cusip": "3137FKUN4",
            "isin": "US3137FKUN40",
            "sedol": null,
            "iso_market_identifier_code": null,
            "market_value_held": 1395.0,
            "notional_value": null,
            "contract_expiry_date": null,
            "quantity_held": null,
            "weighting_sponsor": 2.9163e-06,
            "face": 1258.0,
            "coupon": 3.591,
            "maturity": "2027-10-25",
            "created_at": "2020-12-19T14:20:52.353826Z",
            "updated_at": "2020-12-19T14:20:52.353878Z"
        }
    ]
}
```