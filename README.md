# Adidas-Sales-Performance
Adidas Sales Performance Dashboard

Data Source: https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset

Project Overview
This project focuses on analyzing Adidas sales data to uncover insights into revenue, profitability, costs, and sales distribution across different dimensions such as product, retailer, and geography. The objective was to design a scalable Power BI dashboard with interactive features that allow stakeholders to track KPIs, identify trends, and make data-driven business decisions.
________________________________________
Business Goals
•	Track Total Sales, Units Sold, COGS, Operating Profit, and Profit Margin %.
•	Identify top-performing products and retailers.
•	Compare profitability across states and regions.
•	Understand the impact of sales methods and demographics on performance.
•	Provide what-if pricing analysis to simulate business scenarios.
________________________________________
Approach to Data Analysis
1.	Problem Understanding
o	 Business questions were defined upfront: Which products and retailers drive the most revenue and profit? Which regions are most profitable?
2.	Data Preparation & Modeling
o	Transactional sales dataset was cleaned and validated.
o	A Calendar Table was created with calculated columns for Start of Week, Start of Month, and Start of Year to support time intelligence.
o	Data was modeled in a star schema, connecting facts (Sales) with dimensions (Calendar, Product, Retailer, Geography).
3.	Feature Engineering & DAX Measures
o	Created measures for Total Sales, Units Sold, COGS, Operating Profit, and Profit Margin %.
o	Built advanced measures like Adjusted Price using What-If parameters.
o	Implemented rolling calendar calculations for trend analysis.
4.	Visualization Design
o	Designed KPI cards for quick executive summaries.
o	Used field parameters to allow dynamic comparison of metrics (Revenue, Profit, Units Sold, COGS, Margin %).
o	Built maps for demographics sales by state, bar charts for sales by product & retailer, and combo charts for profit vs margin.
5.	Analysis & Storytelling
o	Combined descriptive and comparative insights into a dashboard with drill-down capability.
o	Added slicers (Date, Region, Sales Method) for self-service analysis.
________________________________________


Key Metrics Implemented
•	Total Sales = SUM of (Price × Units Sold)
•	Total Units Sold
•	Total COGS
•	Operating Profit = Sales – COGS
•	Operating Margin % = Profit ÷ Sales
•	Adjusted Price (What-If Simulation)
•	Rolling Sales over time
________________________________________
Project Findings
1.	Top Products & Retailers
o	A small set of products and retailers contributed disproportionately to total sales.
o	Some high-selling products operated at thin margins, highlighting pricing opportunities.
2.	Profitability Across States
o	High-margin states drove profitability, while some states had strong sales but weak margins.
o	Clear opportunities to reallocate marketing spend toward profitable regions.
3.	Retailer Performance
o	The top 10 retailers accounted for most sales, with varying margin structures.
o	Suggested deeper partnership focus with high-performing retailers.
4.	Demographic Trends
o	Urban and metro states dominated both sales and profits.
o	Smaller cities showed potential for future growth expansion.
5.	Sales Method Impact
o	Online sales were growing faster but at slightly lower margins.
o	Offline/wholesale channels provided more stable, high-margin revenue.
6.	Seasonality & Time Trends
o	Clear seasonal spikes in certain quarters/months.
o	Rolling sales analysis revealed growth momentum in emerging regions.
________________________________________
Dashboard Highlights
•	Dynamic Comparison Chart: Revenue, Profit, Units Sold, COGS, and Profit Margin using Field Parameters.
•	Sales vs Profit Margin Analysis: Combo chart comparing financial performance.
•	Geographic Insights: Interactive maps displaying state-level sales and profitability.
•	Retailer & Product Performance: Ranked tables and bar charts highlighting top contributors.
•	What-If Pricing Simulation: Adjusted Price measure for scenario planning.
________________________________________


Outcome:
The final dashboard enabled Adidas leadership to:
•	Monitor real-time KPIs across multiple dimensions.
•	Identify top and bottom performers (products, retailers, and states).
•	Make data-driven decisions around pricing, regional expansion, and retailer strategy.
•	Scale the model easily for new data and future analysis.
________________________________________
Skills Demonstrated
•	Data Cleaning & Modeling (Star Schema)
•	DAX Measures & Time Intelligence
•	Field Parameters for Interactive Analysis
•	KPI Design & Dashboard Storytelling
•	Business Insights & Recommendations
