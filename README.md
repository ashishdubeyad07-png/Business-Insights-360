**Introduction**

An end-to-end Power BI project built for Atliq Hardware, a hardware distribution company, as part of my data analytics portfolio. The report consolidates sales, finance, forecast accuracy, top customers, and product-level performance into a single interactive dashboard.

**Overview**

Atliq Hardware needed a unified view of business performance across departments. This report brings together sales trends, financial metrics, forecast accuracy, and customer/product insights to support data-driven decision-making — replacing scattered spreadsheets with one interactive tool.

**Business Problem**

Atliq Hardware's leadership relied on scattered Excel reports across sales, finance, and supply chain teams, making it difficult to track performance and forecast reliability in real time. This report consolidates those data sources into a single interactive view.

**Data Source**

Dataset provided as part of Codebasics Bootcamp 5.0, based on a fictional hardware company, Atliq Hardware.

**Tools & Skills Used**

Power BI Desktop — report design & interactivity

DAX — calculated measures and KPIs

Power Query — data cleaning and transformation

Data Modeling — star schema design, relationships

Business analysis: sales performance, financial KPIs, forecast accuracy (AbsError %, Accuracy %)

**Dashboard Sections**

Sales Insights — revenue trends, regional/market performance, customer performance, and product-wise sales

Finance Insights — profit & loss overview, financial KPIs, net sales performance overtime

Forecast Accuracy — comparison of forecast vs. actuals, error analysis

Executive View- providing insights to the top management, top 5 products and customers, revenue by divison and channel 

Top Customers & Products — best-performing customers and products by revenue/quantity

**Data Model**
C:\Users\ashis\OneDrive\Pictures\Screenshots\Star Schema.png.bz2

**Challenges & Solutions**

Challenge: Inconsistent date formats across sales and forecast tables → Solution: Standardized using Power Query transformations
Challenge: Slow report performance with large fact tables → Solution: Optimized data model using star schema and reduced cardinality
Challenge: Presence of bad data like "null values", "blank cells", "duplicate values"- Solution: Transformed and corrected data in Power query editor
