# 🛒 Blinkit Sales Analysis - SQL + Power BI Project

## 📌 Project Overview
Analyzed 8523 records of Blinkit retail dataset to understand sales performance across item types, outlet types, and locations. End-to-end Data Analyst project using PostgreSQL and Power BI.

## 📂 Dataset Details
- Table Name: `blinkit`
- Rows: 8523
- Key Columns: item_type, item_fat_content, outlet_type, outlet_location_type, outlet_size, sales

## 🛠️ Tools Used
- PostgreSQL / pgAdmin 4
- Power BI Desktop

## 📊 SQL Analysis - 8 Queries
1.  **No of total rows** - Data validation
2.  **Item type wise total sales** - Top category
3.  **Fat content wise sales** - Low Fat vs Regular
4.  **Outlet type wise performance** - Supermarket Type1 is best
5.  **Outlet location + size** - Tier wise analysis
6.  **Low visibility yet high sales** - Marketing opportunity
7.  **Null check** - Handled text to float with CAST(sales AS FLOAT)
8.  **Top selling item in every outlet** - Used RANK() OVER(PARTITION BY)

## 📈 Key Insights (Resume madhe takaycha)
- Supermarket Type1 contributes ~60% of total sales
- Low Fat products sell more than Regular
- Tier 3 locations have low sales despite high outlet count
- Fruits & Vegetables and Snack Foods are top categories

## 🚀 Power BI Dashboard
KPIs: Total Sales, Avg Sales | Charts: Item Type vs Sales, Outlet Type Pie, Location Slicer

## 👩‍💻 Author
Radhika | Aspiring Data Analyst | Hyderabad
Skills: SQL | Power BI | Excel

#SQL #PowerBI #HyderabadJobs
