# Malaysia House Price Analysis

## Overview
This project analyzes Malaysia house price data to uncover insights on price distribution across states, house types, and tenure categories.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Dataset
- 2,000 listings
- 8 columns including state, township, house type, tenure, median price, and transactions

## Key Findings
- Putrajaya has the highest median house price
- Kuala Lumpur has extreme outliers reaching up to RM 11 million
- Bungalow is the most expensive house type
- Freehold properties are priced higher than Leasehold
- Johor has the highest transaction volume, likely driven by demand from Singapore buyers
- Penang, Johor, Selangor, and KL show many high-price outliers, indicating active luxury property markets

### Kuala Lumpur Deep Dive
- Four Seasons Place (Service Residence) is the most expensive township at approximately RM 11 million
- Bungalows in KL show the widest price range (RM 1 million to RM 4 million)
- Flat and Apartment prices are concentrated at the lower end, making them more affordable options
- High-end condominiums contribute significantly to KL price outliers, indicating an active luxury condo market

## Limitations
- Data is unevenly distributed across states. States with fewer listings
  (e.g. Perlis, Labuan, Kelantan) may not be representative of actual market conditions
- Data covers 2025 but the specific time period (full year or partial) is unclear
- House type classification was simplified by taking the first listed type for mixed-type townships
- Median_Price definition is unclear — unknown whether this represents all transactions or a specific period
- Analysis is at state level, which may mask significant price variation between townships
- No actual floor area data available, limiting price-to-size analysis

## Files
- `malaysia_house_price_analysis.ipynb` — Main analysis notebook
