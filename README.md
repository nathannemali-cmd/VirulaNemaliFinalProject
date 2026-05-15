# Inflation and Sector Performance Analysis

Analysis of inflation, interest rates, and S&P 500 sector performance using Python, FRED data, and Yahoo Finance.

## Overview

This project explores how inflation and interest rate volatility affect major sectors of the S&P 500, including Technology, Energy, Financials, and Utilities. By combining macroeconomic data from FRED with market data from Yahoo Finance, we analyzed how different sectors respond during periods of economic uncertainty and inflation volatility.

Using statistical modeling, correlation analysis, and custom visualizations, we identified which sectors are most sensitive to inflationary conditions and compared their long-term performance over time.

---

## Research Questions

- Which sectors are most correlated with inflation?
- How do interest rate changes impact sector returns?
- Which sectors perform best during periods of high inflation volatility?
- How did major macroeconomic events affect sector growth?

---

## Data Sources

- FRED (Federal Reserve Economic Data)
  - CPIAUCSL (Consumer Price Index)
  - FEDFUNDS (Federal Funds Interest Rate)

- Yahoo Finance
  - XLK — Technology
  - XLF — Financials
  - XLE — Energy
  - XLU — Utilities
  - ^GSPC — S&P 500

---

## Techniques Used

- OLS Regression
- Correlation Analysis
- Heatmap Correlation Matrix
- Bubble Plot Visualization
- Time Series Analysis
- Data Merging and Cleaning with Pandas

---

## Inflation Trend Over Time

The graph below shows the long-term increase in inflation over the selected time period. Major increases in inflation can be seen after the 2008 financial crisis and during the post-COVID inflation surge beginning in 2021.

![Inflation Trend](Inflation.png)

---

## Correlation Heatmap

This heatmap compares the correlation between sectors, inflation, interest rate changes, and the S&P 500. Energy showed the strongest relationship with inflation, while Technology and Financials had the strongest correlation with the overall market.

![Correlation Heatmap](HeatMap.png)

---

## Bubble Plot Visualization

This bubble plot compares sectors using three dimensions at once:
- X-axis → correlation with inflation
- Y-axis → average return
- Bubble size → volatility/risk

The visualization shows that Energy had the strongest inflation relationship, while Technology produced the highest average return over time.

![Bubble Plot](Bubble.png)

---

## Main Findings

- Energy showed the strongest relationship with inflation.
- Technology produced the highest long-term return.
- Utilities were more stable but had lower returns.
- Inflation volatility significantly impacted sector behavior.
- Different sectors react very differently during periods of economic uncertainty.

---

## Future Improvements

If given more time and resources, we would expand this project by:
- Including additional sectors and international markets
- Applying machine learning prediction models
- Incorporating unemployment and GDP data
- Comparing inflationary periods across different decades

---

## Authors

Nathan Nemali and Daniel Virula
