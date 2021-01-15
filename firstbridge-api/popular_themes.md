# Pre-filtered ETF Categories

Returns all ETFs in specified pre-filtered ETF categories. 
Sample API call
```
GET /yt/v1.0/us/lists?filter=esg
```

## Categories
```
ESG ETFs
/yt/v1.0/us/lists?filter=esg
Criteria: social_environmental_type has any non-blank value except 'Not Applicable'

Leveraged and inverse ETFs
/yt/v1.0/us/lists?filter=leveraged_inverse
Criteria: inverse_leveraged has any non-blank value except 'Not Applicable'

Volatility and beta weighted ETFs
/yt/v1.0/us/lists?filter=low_volatility  
Criteria: index_weighting_scheme = 'Volatility / Beta Weighted'

Industry Sector ETFs
/yt/v1.0/us/lists?filter=sector_industry
Criteria: sector has any non-blank value except 'Not Applicable'

Emerging Market Bond ETFs
/yt/v1.0/us/lists?filter=emerging_bond 
Criteria: asset_class = 'Bonds' and developed_emerging = 'Emerging Market Funds'

Exchange Traded Note (ETN)
/yt/v1.0/us/lists?filter= etn
Criteria: LegalStructure = 'ETN'

Corporate Bond ETFs
/yt/v1.0/us/lists?filter=corporate_bond  
Criteria:  bond_type = 'Corporate'

Currency Hedged ETFs
/yt/v1.0/us/lists?filter=currency_hedged
Criteria: currency_hedged = 'Yes'

Active Non-Indexed ETFs
/yt/v1.0/us/lists?filter=active 
Criteria: index_linked = 'Active'

Dividend ETFs
/yt/v1.0/us/lists?filter=dividend
Criteria: dividend_type has any non-blank value except 'Not Applicable'
```

