Sales Analytics Dashboard
1. Introduction

This project analyzes global sales performance across multiple regions, product categories, sales channels, employees, and customers using a relational (star schema) dataset. Raw transactional data was cleaned and validated using Python, then transformed into an interactive Power BI dashboard to help stakeholders understand what's driving revenue and profit across the business.

2. Business Problem

A retail/sales organization's transactional data was spread across multiple related tables (customers, products, employees, geography, dates, and sales transactions), but the raw data contained quality issues — duplicate records, missing values, inconsistent formatting, invalid numeric entries, and orphaned references — making it unreliable for direct analysis or reporting.

Without a clean, unified view of this data, the business had no easy way to answer fundamental questions like:

Where is revenue actually coming from?
Which products and categories are worth prioritizing?
Are discounts eating into profit margins?
Which customers and employees drive the most value?

3. Dashboard's Goal

The goal of this dashboard is to turn raw, fragmented sales data into a single, trustworthy source of truth that helps stakeholders quickly answer:

What are the overall sales and profit trends over time?
Which products/categories drive the most revenue and profit?
How do sales vary by region/country and by channel?
Who are the top-performing employees and highest-value customers?

The dashboard is built across 3 pages — Overview, Product Performance, and Customer & Employee Performance — so each audience (leadership, product teams, sales teams) can find what's relevant to them without digging through raw data.

4. Key Visuals

Page 1 — Overview sets the stage with headline numbers (total sales, orders, profit) alongside where that revenue is coming from — top categories, top countries, and how sales are trending quarter over quarter. The channel breakdown shows how customers are actually buying (Retail, Online, Partner, Phone).

Page 2 — Product Performance digs into what's actually selling. Revenue leaders and profit leaders are shown side by side deliberately — a product that sells a lot isn't always the one making the most money, and this page makes that gap visible. Category-level comparison and units-sold trends round out the product story.

Page 3 — Customer & Employee Performance shifts focus to who is driving the business — both on the selling side (employee contribution) and the buying side (customer value and loyalty tiers). The goal here is to spot where the business is either well-diversified or overly dependent on a small group.

5. Insights
Clothing is the top-performing category, generating the highest revenue, followed closely by Accessories and Kitchen.
Revenue is remarkably evenly spread across countries — no single market dominates, with the top 7 countries all falling within a narrow range of each other.
Sales channels are almost perfectly balanced, each contributing roughly a quarter of total sales — showing a well-diversified, channel-agnostic customer base.
Employee performance is mostly consistent, with a handful of standout performers rather than extreme outliers — indicating low dependency risk on any single employee.
A small segment of customers significantly outspends the average, spending nearly 2x the typical customer — a clear opportunity for targeted retention efforts.
Top-performing products span multiple categories, showing that revenue leadership isn't concentrated in just one product line.
Quarterly sales show noticeable volatility, with sharp spikes and dips rather than a steady trend — pointing to seasonal demand or inconsistent promotional activity worth investigating further.
6. Business Impact

This dashboard gives the business a reliable, self-serve way to monitor performance without relying on manual reporting. It enables:

Smarter inventory and marketing focus by clearly identifying which products and categories actually drive profit, not just revenue.
Reduced concentration risk, since sales are shown to be well-diversified across channels, countries, and employees rather than dependent on any single one.
Targeted customer retention strategy, by surfacing high-value customers who could be prioritized for loyalty programs.
Better-informed promotional planning, since visible quarterly volatility highlights where discounting or seasonal strategy needs closer review.
Overall, the dashboard turns messy, disconnected sales data into a decision-ready view that supports both day-to-day sales tracking and longer-term strategic planning.
7. Tools Used

This project was built using Python (pandas) for data cleaning, validation, and transformation, and Power BI for data modeling, DAX-based calculations, and building the interactive dashboard.

Dashboard Images : 
1] Sale Performance Report :
https://github.com/Izmomin14/sales-analytics-dashboard/blob/main/Sales%20Dashbaord.png

2] Product Performance Report :
https://github.com/Izmomin14/sales-analytics-dashboard/blob/main/Products%20Dasboard.png

3] Employee and Customer Report : 
https://github.com/Izmomin14/sales-analytics-dashboard/blob/main/Employee%20and%20Customer%20png.png

