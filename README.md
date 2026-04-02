# Quick-Commerce-Analytics-Dashboard-Power-BI-
An end-to-end Power BI analytics project for a Quick Commerce business that analyzes sales, customer behavior, rider operations, and inventory performance to uncover profitability gaps and operational inefficiencies.

Project Objective:
This project aims to simulate a real-world quick commerce (Q-commerce) business scenario where rapid growth in orders and GMV does not necessarily translate into profitability.

The goal was to:

-Identify profitability gaps across zones
-Analyze customer behavior and discount dependency
-Evaluate rider efficiency and delivery performance
-Monitor inventory health and stock risks

Business Context:
Quick commerce businesses operate on speed, convenience, and high-frequency transactions, but often face:

-High operational costs
-Heavy discounting strategies
-Supply chain inefficiencies
-Delivery constraints

Dashboard Structure

The solution is divided into five analytical layers, each addressing a key business function:

Sales & Profitability Analysis:

Focuses on overall business performance using KPIs such as:

-Total Revenue & Orders
-Average Order Value (AOV)
-Net Profit & Net Profit %
-Revenue trends over time
-GMV vs Profit comparison

Customer Behavior & Retention:

Analyzes customer engagement and loyalty:
-Total vs Recent Customers
-Repeat Customer %
-Promo Dependency %
-Average Basket Size

Rider & Delivery Operations:

Evaluates operational efficiency:
-Rider Utilization Rate
-Orders Delivered
-On-Time Delivery %
-Average Delivery Time

Inventory & Supply Chain Monitoring:

Tracks stock efficiency and risks:
-Current Stock & SKU Count
-Low Stock & Reorder Levels
-Safety Breach %

Zone-Level Performance (Drill-through Enabled):

Provides granular insights at city/zone level:
-GMV & Orders
-Discount %
-AOV & COGS
-Net Profit per Order

Technical Implementation:
-Power BI for visualization and storytelling
-DAX for KPI calculations (GMV, Profit %, AOV, etc.)
-Power Query for data transformation
-Data Modeling using fact and dimension tables
-Drill-through functionality for deep-dive analysis
-Dynamic slicers for interactive exploration

Key Insights & Business Impact:

Profitability Gap
-Despite strong revenue growth, some zones show declining or negative Net Profit per Order, indicating unsustainable expansion.

Discount Inefficiency
-High Promo Dependency % is not translating into better Repeat Customer %, suggesting:
-Discounts are attracting price-sensitive, low-loyalty customers

Operational Imbalance
-Rider workload varies significantly across cities:
-Some riders are overloaded, while others are underutilized
-Leading to delays and inefficiencies

Inventory Risks
-Significant number of SKUs are:
-Below reorder levels
-Breaching safety stock
This impacts order fulfillment and customer satisfaction

Hidden Underperforming Zones
-Zone-level analysis reveals:
-Some regions with high GMV are actually burning cash
-While others are highly efficient but under-scaled
