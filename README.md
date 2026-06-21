# GlamGlow-D2C-Brand-Impact-Analysis-
End-to-end Power BI case study analyzing D2C sales, marketing performance, and profitability for Goodly using data modeling, DAX, and business intelligence.



**Business Problem**

Glamglow, a growing D2C brand, operates across multiple sales channels including Quick Commerce and shipped orders. The company wants to understand sales performance, marketing efficiency, and profitability across products, channels, and campaigns.

The challenge is fragmented data across multiple sources including sales, cost structures, agreement codes, and ad campaign data.

The objective of this project is to consolidate all data sources into a single analytical model and build an interactive Power BI dashboard to monitor business performance and support strategic decision-making.

**Project Objectives**
Analyze revenue trends across products and channels
Track order volume and units sold
Measure return rate and identify risk areas
Evaluate ad spend and campaign effectiveness
Monitor marketing funnel performance
Calculate ROAS and profitability metrics
Deliver actionable business recommendations



**Key DAX Measures**
Total Revenue = SUM(Fact_All_Sales[Revenue])

Total Orders = DISTINCTCOUNT(Fact_All_Sales[Order ID])

Units Sold = SUM(Fact_All_Sales[Quantity])

ROAS = DIVIDE([Total Revenue], [Ad Spend], 0)

**Key Insights**

Example:

Quick Commerce contributes highest revenue
Certain categories generate high sales but low margin
Paid campaigns show varying ROAS across channels
Return rate impacts profitability in selected categories


**Recommendations**

Example:

Increase investment in high-ROAS campaigns
Reduce focus on low-margin categories
Improve retention for high-return segments
Optimize marketing spend allocation
Gross Margin = [Total Revenue] - [Total Cost]
