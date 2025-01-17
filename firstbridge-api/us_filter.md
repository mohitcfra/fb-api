Returns the detailed classification & reference data for any ETF that meets the filter criteria. For example: `/yt/v1.0/etf/us/filter?field=sponsor&value=invesco` will return information for all ETFs where Invesco is the sponsor.  

Filtering is supported on most fields, including:  

```
sponsor  
exchange_code  
asset_class  
listing_region  
is_live_listed  
cusip  
isin  
sedol  
inception_date  
legal_structure  
exchange_name  
sector  
industry  
sub_industry  
commodity_types  
energy_type
agricultural_type  
metal_type  
market_cap_range  
growth_value_tilt  
continent  
specialized_region  
specific_country  
inverse_leveraged  
index_name  
income_etf_category  
```
If you want all ETFs for a given filtering criterion in single api call, you should set pagination=off
`/yt/v1.0/etf/us/filter?field=asset_class&value=Equities (Stocks)&pagination=off`

Request:
```
GET 
/yt/v1.0/etf/us/filter?field=sponsor&value=invesco
```
Response:
```
{
    "count": 224,
    "next": true,
    "previous": false,
    "results": [
        {
            "firstbridge_id": "715a35b4ae4e4a399ee43b857be97a85",
            "composite_name": "Invesco BLDRS Emerging Markets 50 ADR Index Fund",
            "composite_ticker": "ADRE",
            "sponsor": "Invesco",
            "isin": "US46090C3051",
            "sedol": "BDQYP45",
            "share_class_figi": "BBG001SBZBZ1",
            "original_inception_date": "2002-11-13",
            "inception_date": "2002-11-13",
            "close_date": null,
            "is_live_listed": true,
            "legal_structure": "Unit Investment Trust",
            "exchange_name": "NASDAQ",
            "exchange_code": "XNAS",
            "net_expense_ratio": 0.0018,
            "asset_class": "Equities (Stocks)",
            "other_asset_types": "Not Applicable",
            "market_cap_range": "Large Cap",
            "growth_value_tilt": "Core / Blend",
            "growth_type": "Not Applicable",
            "value_type": "Not Applicable",
            "sector": "Not Applicable",
            "industry": "Not Applicable",
            "sub_industry": "Not Applicable",
            "cross_sector_theme": "Not Applicable",
            "us_or_ex_us": "International",
            "developed_emerging": "Emerging Market Funds",
            "specialized_region": "Not Applicable",
            "continent": "Not Applicable",
            "latin_america_sub_group": "Not Applicable",
            "europe_sub_group": "Not Applicable",
            "asia_sub_group": "Not Applicable",
            "specific_country": "Not Applicable",
            "china_listing_location": "Not Applicable",
            "real_estate": "Not Applicable",
            "index_weighting_scheme": "Market Cap Weighted",
            "market_cap_weighting_type": "Market Cap Weighting - Float Adjusted",
            "fundamental_weighting_type": "Not Applicable",
            "dividend_weighting_type": "Not Applicable",
            "bond_type": "Not Applicable",
            "government_bond_types": "Not Applicable",
            "municipal_bond_region": "Not Applicable",
            "mortgage_bond_types": "Not Applicable",
            "bond_tax_status": "Not Applicable",
            "credit_quality": "Not Applicable",
            "average_maturity": "Not Applicable",
            "specific_maturity_year": "Not Applicable",
            "bond_currency_denomination": "Not Applicable",
            "commodity_types": "Not Applicable",
            "energy_type": "Not Applicable",
            "agricultural_type": "Not Applicable",
            "metal_type": "Not Applicable",
            "inverse_leveraged": "Not Applicable",
            "target_date_multi_asset_type": "Not Applicable",
            "currency_hedged": "No",
            "currency_pair": "Not Applicable",
            "social_environmental_type": "Not Applicable",
            "clean_energy_type": "Not Applicable",
            "dividend_type": "Not Applicable",
            "quant_strategies_type": "Not Applicable",
            "other_quant_models": "Not Applicable",
            "hedge_fund_type": "Not Applicable",
            "derivatives_based": "Not Primarily Derivatives Based",
            "index_linked": "Passive",
            "index_name": "BNY Mellon Emerging Markets 50 ADR Index",
            "parent_index": "BNY Mellon ADR Index",
            "index_provider": "BNY Mellon",
            "fund_family": "Invesco QQQ / BLDRS Funds",
            "index_ticker": "BKTEMT",
            "etf_description": "The Invesco BLDRS Emerging Markets 50 ADR Index Fund (Fund) seeks to provide investment results that correspond generally, before fees and expenses, to the price and yield performance of the BNY Mellon Emerging Markets 50 ADR Index (Index). The Fund normally holds at least 95% of its total assets in depositary receipts (DR) that comprise the Index. The Index is capitalization-weighted and designed to track the performance of approximately 50 emerging market-based DRs. The Fund and the Index are rebalanced and reconstituted quarterly. The Fund is an \"index fund\" that holds publicly traded DRs, negotiable U.S. securities that generally represent a non-U.S. companys publicly traded equity or debt, of non-U.S. companies in a particular geographic region or market represented by a specified relevant benchmark BNY Mellon ADR Index.",
            "etn_issuing_bank": "Not Applicable",
            "etn_maturity_date": null,
            "livestock": "Not Applicable",
            "dynamic_futures_roll": "Not Applicable",
            "index_provider_code": "BNYMELLON",
            "etf_type": "Global Ex. US Equities",
            "single_category_designation": "Global or ExUS Equities - Broad / Regional",
            "ucits": "No",
            "replication_structure": "Physical",
            "domicile": "US",
            "base_currency": "USD",
            "listing_currency": "USD",
            "fund_listing_date": "2002-11-13",
            "listing_country_code": "US",
            "primary_ticker": "ADRE:US",
            "primary_ticker_country_code": "US",
            "primary_listing_region": "US",
            "listing_region": "US",
            "smart_vs_traditional_beta": "TraditionalBeta",
            "smart_vs_traditional_beta_level2": "Broad/Size - Cap Weighted",
            "income_etf_category": "Not Applicable",
            "interest_rate_hedged": null,
            "etp_structure_type": "ETF (Open end fund)",
            "data_status": "A",
            "firstbridge_parent_id": "715a35b4ae4e4a399ee43b857be97a85"
        }
    ]
}
```
