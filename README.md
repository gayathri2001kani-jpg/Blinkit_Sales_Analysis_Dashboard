Blinkit Sales Analysis Dashboard – Power BI
📊 Project Overview

This project focuses on analyzing Blinkit sales data using Power BI to uncover meaningful insights into sales performance, product categories, outlet performance, customer preferences, and other key business metrics.

The dashboard is designed using a Galaxy Schema (Fact Constellation Schema), which allows multiple fact tables to share common dimension tables. This approach provides a scalable and structured data model for performing detailed analysis across different business processes.

🎯 Objectives
Analyze overall sales and revenue performance.
Identify top-performing product categories and items.
Compare sales performance across different outlet types and locations.
Understand customer purchasing patterns and preferences.
Analyze outlet establishment trends and performance.
Track key performance indicators (KPIs) through interactive dashboards.
Provide actionable insights to support data-driven business decisions.

🏗️ Data Modeling – Galaxy Schema

The project uses a Galaxy Schema consisting of multiple fact tables connected through shared dimension tables.

Fact Tables
Sales Fact – Contains sales-related measures such as total sales, quantity sold, and item-level sales.
Outlet/Performance Fact – Stores outlet-level performance metrics for comparative analysis.
Dimension Tables
Item Dimension – Item type, fat content, item attributes, etc.
Outlet Dimension – Outlet type, outlet size, location, and establishment information.
Date Dimension – Date-based attributes used for time-series analysis.

The Galaxy Schema improves data organization, reduces redundancy, and enables flexible analysis across multiple dimensions.

📈 Dashboard Features

The Power BI dashboard includes:

Total Sales
Total Items Sold
Average Sales
Average Rating
Sales by Item Type
Sales by Outlet Type
Sales by Outlet Location
Sales by Outlet Size
Sales Trend Analysis
Fat Content Analysis
Interactive slicers and filters
KPI cards and visual analytics
🛠️ Tools & Technologies
Power BI
Power Query
DAX
Data Modeling
Galaxy Schema / Fact Constellation Schema
Microsoft Excel / CSV

🔍 Key Insights

The dashboard helps identify:

Which product categories generate the highest sales.
Which outlet types contribute most to overall revenue.
How outlet size and location affect sales performance.
Customer preferences based on item characteristics.
Sales patterns and trends across different dimensions.
Areas where business performance can potentially be improved.

📁 Project Structure
Blinkit-Sales-Analysis-PowerBI/
│
├── Dataset/
│   └── blinkit_sales_data.csv
│
├── PowerBI/
│   └── Blinkit_Sales_Analysis.pbix
│
├── Dashboard/
│   └── dashboard_screenshot.png
│
└── README.md

🚀 Conclusion

This project demonstrates how Power BI, DAX, Power Query, and dimensional data modeling can be combined to transform raw Blinkit sales data into an interactive business intelligence dashboard.

The use of a Galaxy Schema provides a robust data model that supports cross-dimensional analysis and makes the dashboard easier to extend for future analytical requirements.
