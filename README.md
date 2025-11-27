# Blinkit Business Intelligence Dashboard

## Overview

This project presents a fully interactive **Power BI dashboard** for Blinkit, built using datasets taken from kaggle, processed in **SQL Server Management Studio (SSMS)**. It delivers actionable insights into sales performance, customer behavior, campaign effectiveness, and operational metrics. The dashboard supports strategic decisions across marketing, inventory, and customer engagement.

---

## Tools & Technologies Used


**SQL Server Management Studio (SSMS)** 
Data cleaning, transformation, schema design 

**Power BI Desktop** 
Data modeling, Relationships, DAX measures, dashboard creation 

**CSV/XLSX Files** 
Raw and enriched data sources 

---

## Data Sources

All datasets were stored locally and imported from:

### Raw Tables Used


 `binhh_customers.csv`  Customer profiles and segmentation 
 `binhh_customer_feedback.csv`  Ratings and satisfaction data 
 `binhh_delivery_performance.csv`  On-time vs late delivery tracking 
 `binhh_inventory.csv`  Current stock levels 
 `binhh_inventoryNews.csv`  Inventory updates and restock info 
 `binhh_marketing_performance.csv`  Campaign impressions, clicks, conversions 
 `binhh_orders.csv`  Order-level details including timestamps and amounts 
 `binhh_order_teams.csv`  Delivery team assignments
 `binhh_products.csv`  Product catalog and categories 
 `Category_Icons.xlsx`  Icons for category visuals 
 `binhh_icons.xlsx`  Custom icons for dashboard visuals 

---

## Dashboard 1: Customer & Order Insights

### Filters
- Month
- Area
- Brand
- Campaign Name

### 📉 Visuals
- Customer Type (New vs Returning)
- Satisfaction Ratings (Positive, Neutral, Negative)
- Ratings Breakdown (Pie Chart)
- Top Selling Items

---

## Dashboard 2: Sales & Campaign Performance

### Filters
- Month
- Area
- Brand
- Time of Day: Morning, Afternoon, Evening
- Top (1,3,5,10)

### Visuals
- Monthly Sales Trend 
- Sales by Hour (Donut Chart)
- Inventory Distribution (Pie Chart)

---

## Learning Outcomes

- SQL-based data cleaning and schema design
- Power BI dashboarding with DAX logic
- Business-centric analysis of e-commerce KPIs
- Visual storytelling for operational and marketing performance

---
