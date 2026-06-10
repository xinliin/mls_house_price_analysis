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

## Limitations
- Data is unevenly distributed across states. States with fewer listings
  (e.g. Perlis, Labuan, Kelantan) may not be representative of
  actual market conditions.
- Data covers 2025 but the specific time period (full year or partial)
  is unclear, which may affect trend analysis.
- House type classification was simplified by taking the first listed type
  for mixed-type townships, which may lose some information.
- Median_Price definition is unclear — it is unknown whether this represents
  all transactions or a specific period within 2025.
- Analysis is at state level, which may mask significant price variation
  between townships within the same state.
- No actual floor area data available, limiting price-to-size analysis.

## Files
- `malaysia_house_price_analysis.ipynb` — Main analysis notebook
