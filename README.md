# Nike-P-L-Dashboard

This Power BI dashboard was built to give a centralized view of Nike's financial performance across two main areas: overall P&L health and regional/product-level breakdown.

1. P&L Overview - https://github.com/Yergataikagan/Nike-P-L-Dashboard/blob/main/Nike%20P%26L.png

Tracks key financial metrics including total revenue, gross margin, and net income, and visualizes how each P&L line item (COGS through EBITDA down to Net Income) performs year over year from 2017 to 2021, with a dynamic year-range slicer for flexible filtering.

3. Revenue Breakdown

Goes deeper into revenue composition, showing Men's vs Women's Shoe Revenue trends across years using a stacked bar chart, alongside a regional revenue split (Northeast, Midwest, West, South, Southeast) visualized as a donut chart.


**Dataset**
Source: Fictional Nike case study dataset covering 28 store locations across the US and 5 fiscal years (2017–2021), structured across 5 tables:
https://github.com/Yergataikagan/Nike-P-L-Dashboard/blob/main/72NikeCaseStudyDataset-230301-172152%20(2).xlsx

FactPLTran — Monthly P&L transactions per store (revenue, COGS, expenses, taxes)

DimStore — Store details: city, state, and region (Northeast, Midwest, West, South, Southeast)

DimAcc — Chart of accounts mapping transaction types

DimPLLineItems — P&L line item hierarchy for matrix visual

DimDate — Date table for time intelligence calculations




**Key Insights:**

2020 revenue spike - Total revenue jumped to $112.9M in 2020, more than triple the previous year, driven by strong growth in both Men's and Women's shoe categories

Margin pressure in 2019 - Gross Margin % dropped to 40.5% in 2019, the lowest across all five years, suggesting rising costs relative to revenue

Best margin year in 2018 - Gross Margin % peaked at 61.5%, indicating the most cost-efficient year across the period

Net Income volatility - The business swung to a net loss of -$532K in 2020 despite record revenue, pointing to a significant spike in operating and other expenses that year

Regional concentration - The West (24.4%) and Midwest (26.1%) together account for over half of total revenue, making them the core markets

Women's shoes catching up - Women's Shoe Revenue consistently grew and nearly matched Men's in several years, suggesting a shift in product demand mix




**Skills & Tools Used**

Power BI   DAX Expressions 

Data Transformation 

KPIs & Slicers Matrices & Charts 

Dashboard Design 

Data Modeling   Financial Analysis
