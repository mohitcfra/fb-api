Returns the unique possible field values for every field in the classification data. For e.g. ‘/yt/v1.0/etf/distinct/listing/us?field=sponsor’ will return a list of all the sponsors.   
Listing is supported on most fields, including:  

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

Request
```
GET
/yt/v1.0/etf/distinct/listing/us?field=sponsor
```

Response:
```
[
    "Main Management",
    "Wisdom Tree",
    "Invesco",
    "Pacer Financial",
    "Van Eck Associates Corporation",
    "ProShares",
    "Barclays iPath",
    "Credit Suisse",
    "DWS",
    "Blackrock (iShares)",
    "Tuttle Tactical Management",
    "Index IQ",
    "Merlyn AI",
    "Direxion Shares",
    "Innovator Management",
    "Fidelity",
    "State Street (SPDR)",
    "UBS",
    "Vanguard",
    "Bank of Montreal",
    "BNY Mellon",
    "First Trust",
    "Simplify ETF",
    "Motley Fool Asset Management",
    "Schwab",
    "U.S. Global Investors",
    "Global X",
    "Franklin Templeton",
    "WBI Shares",
    "Howard Capital Management",
    "PIMCO",
    "Syntax",
    "AGFiQ",
    "Exponential ETFs",
    "JPMorgan Chase",
    "Virtus ETF Solutions",
    "Liquid Strategies",
    "ALPS",
    "Goldman Sachs",
    "John Hancock Funds",
    "Flexshares (Northern Trust)",
    "Krane Shares",
    "ETF Managers Group",
    "Nuveen",
    "AllianzIM",
    "LeaderShares",
    "United States Commodity Funds",
    "Toews Funds",
    "GraniteShares",
    "Nationwide",
    "TrueShares",
    "Natixis",
    "Barclays",
    "Teucrium",
    "Defiance ETFs",
    "PGIM Investments",
    "ELEMENTS",
    "Premise Capital",
    "VictoryShares",
    "TIS Advisors",
    "Beyond Investing",
    "Amplify Investments",
    "Infusive Asset Management",
    "CSOP Asset Management",
    "Roundhill Financial",
    "Legg Mason",
    "Alpha Architect",
    "Metaurus Advisors",
    "Saba Capital",
    "Inspire Investing",
    "Adasina Social Capital",
    "Aberdeen",
    "American Century Investments",
    "Distillate Capital",
    "Cambria Funds",
    "DeltaShares",
    "Janus",
    "Leatherback Asset Management",
    "Acquirers Funds",
    "Exchange Traded Concepts",
    "FormulaFolio Investments",
    "Advanced Research Investment Solutions",
    "Avantis Investors",
    "Cabana ETF",
    "TrimTabs Asset Management",
    "Qraft Technologies",
    "Aptus Capital Advisors",
    "Advisor Shares",
    "Sofi",
    "Regents Park Funds",
    "CBOE Vest",
    "Spinnaker ETF Trust",
    "Principal Financial Services",
    "Changebridge Capital",
    "ARK Funds",
    "Reality Shares",
    "Global Beta Advisors",
    "Columbia Management",
    "Sage Advisory Services",
    "ACSI Funds",
    "Pacific Global Advisors",
    "iM Global Partner",
    "Rareview Funds",
    "AltShares",
    "Eaton Vance",
    "Advisors Asset Management",
    "Impact Shares",
    "Counterpoint Mutual Funds",
    "ArrowShares",
    "OShares Investments",
    "Sterling Capital",
    "Hartford Funds",
    "Vident",
    "2ndVote Funds",
    "Aware Asset Management",
    "Emles",
    "ProcureAM",
    "SmartETFs",
    "Dimensional",
    "Little Harbor Advisors",
    "Sprott Asset Management",
    "Leuthold Group",
    "Davis Advisors",
    "Esoterica Capital",
    "Renaissance",
    "Morgan Stanley",
    "ACV ETF",
    "Alternative Access",
    "Reflection Asset Management",
    "T. Rowe Price",
    "Change Finance",
    "Wahed Invest",
    "Hoya Capital",
    "Highland Funds",
    "Strategy Shares",
    "Siren ETF",
    "Point Bridge Capital",
    "Ballast AM",
    "OBP Capital",
    "Gavekal Capital",
    "Vesper Capital Management",
    "EntrepreneurShares",
    "SPFunds",
    "Timothy Plan",
    "ATAC Funds",
    "AlphaClone",
    "Whitford Asset Management",
    "Quadratic Capital Management",
    "Merk Investments",
    "Day Hagan",
    "CornerCap",
    "Gadsden",
    "AlphaMark",
    "Absolute Investment Advisers"
]
```
