# 🌍 Kenya Agricultural Price Intelligence Dashboard

## Project Overview

An agricultural intelligence project analysing historical commodity prices in Kenya to identify market trends, seasonal patterns and year-on-year changes.

Developed as part of my work at OpenTrace, the project uses SQL and Google BigQuery to integrate and analyse agricultural datasets from FAOSTAT, FEWS NET and the World Food Programme (WFP). The goal is to transform fragmented data into structured insights that support agricultural market analysis and informed decision-making.

## Objectives

- Analyse historical agricultural commodity prices.
- Examine retail and wholesale price movements.
- Calculate average, median, minimum and maximum prices.
- Evaluate year-on-year growth and seasonal patterns.
- Assess data quality, coverage and historical availability.
- Develop an interactive Looker Studio dashboard.

## Key Areas of Work

📊 **Agricultural Price Analysis:** Examining historical prices, identifying trends, seasonal patterns and annual changes across retail and wholesale markets.

🌾 **Agricultural Data Integration:** Combining datasets from multiple sources to support consistent analytical workflows.

🔍 **Data Quality and Coverage:** Evaluating data availability, historical coverage, consistency and limitations.

📈 **Data-Driven Insights:** Translating agricultural data into findings that support market analysis and informed decisions.

**The Bigger Picture:** Strengthening the data foundations needed to understand agricultural markets, identify emerging risks and support better decisions across African food systems.

## Technology Stack

- SQL and Google BigQuery
- Looker Studio
- Microsoft Excel
- Data Analytics and Visualisation

## Dataset at a Glance

| Source | Observations | Share | Products |
|---|---:|---:|---:|
| FEWS NET | 22,717 | 65.2% | 39 |
| FAOSTAT | 8,747 | 25.1% | 131 |
| WFP | 3,400 | 9.8% | 34 |
| **Total** | **34,864** | **100%** | — 

## Project Coverage

- **Country:** Kenya
- **Commodities:** 25 selected commodities.
- **Data:** Historical agricultural market prices.

## Key Findings: Cross-Country Comparison
🌽 Maize (Corn)
FAOSTAT – Producer Prices
- Nominal producer prices increased from 2,870 SLC/tonne in 1991 to 62,812 SLC/tonne in 2024.
- Major annual increases occurred in 1993 (+238%), 1997 (+52.6%), 2008 (+56%) and 2022 (+76.5%).
- In 2022, prices increased from 30,027 to 53,010 SLC/tonne.
- Missing observations in 2017–2018 limit interpretation of the historical trend.
FAOSTAT – USD Prices
- Prices increased from $104/tonne in 1991 to $466/tonne in 2024, approximately 347%.
- The 2022 price increase was approximately 64% in USD terms.
- In 2023, prices increased by 15% in LCU terms but declined by 3% in USD terms, highlighting the influence of currency movements.
WFP – White Maize Retail (2006–2020)
- Moderate seasonal variation, with a March average low of 43.85 and July peak of 47.68.
- Seasonal price spread was approximately 8.7%.
- Interannual variation was greater than seasonal variation, with June prices ranging from 20.75 to 68.54.
FEWS NET – Maize Meal Retail (2006–2023)
- Prices remained relatively stable within the 100–115 range during 2011–2021.
- A significant increase occurred in 2022 (+72%), reaching 181, followed by 208 in 2023 (+15%).
- The 2023 average is based on five months and should be treated as partial.
🫘 Beans
WFP – Mixed Beans Retail (2006–2023)
- Prices increased from 46 in 2006 to 127 in 2022, approximately 177%.
- Major increases occurred in 2008 (+80%) and 2011 (+53%).
- The 2023 partial-year average reached 158 (+24%), based on six months.
FEWS NET – Dry Beans Wholesale (2006–2020)
- Complete 12-month annual coverage throughout the period.
- The dataset demonstrates a clear long-term upward price trend.

```
## Recommendations

Based on the agricultural price analysis and data quality assessment, the following recommendations were identified:

. **Standardise Currency and Units:** Standardise LCU, SLC and USD labels, validate missing years and resolve inconsistencies in product           mappings before developing forecasting models.

. **Improve Monthly Data Coverage:** Track monthly observations across FEWS NET and WFP datasets. Flag incomplete years and separately classify   partial-year records to prevent misleading annual comparisons.

. **Develop a Multi-Source Maize Forecasting Model:** Build a forecasting model using lagged prices, rolling averages, year-on-year (YoY)         growth rates and seasonal patterns to improve commodity price prediction.

. **Investigate 2022–2023 Price Shocks:** Examine significant price movements alongside inflation, exchange rates, climate conditions and         agricultural production data to identify potential contributing factors.
. **Calculate Real-Price Indicators:** Incorporate available economic deflators to distinguish nominal price increases from real price changes   and provide a more accurate understanding of agricultural commodity price movements.
## Dashboard

[View the Interactive Looker Studio Dashboard](ADD_YOUR_DASHBOARD_LINK_HERE)

## Author

**Philip Ibingha**

Data Scientist | Agricultural Intelligence | SQL | Python | BigQuery

- [GitHub](https://github.com/philipibingha07-code)
- [LinkedIn](https://www.linkedin.com/in/philip-ibingha-a296a5380/)

---

*Building data-driven insights for stronger agricultural intelligence across Africa.*
