Blinkit Grocery Sales Dashboard (Power BI Project)
📌 Project Title

Blinkit Sales & Outlet Performance Analysis Dashboard

📊 Project Overview

Developed an interactive Power BI dashboard to analyze Blinkit grocery sales performance across outlet types, sizes, item categories, and customer ratings.

The dashboard provides insights into:

Total Sales Performance

Outlet-wise Contribution

Item Category Trends

Fat Content Analysis

Outlet Establishment Trends

Rating & Sales Correlation

📁 Dataset Used

Blinkit Grocery Data.xlsx

Columns Used:

Item Identifier

Item Type

Item Fat Content

Item Visibility

Item Weight

Sales

Rating

Outlet Identifier

Outlet Establishment Year

Outlet Size

Outlet Location Type

Outlet Type

📈 KPI Cards Created (Top Section)
KPI	Value	Formula Used
💰 Total Sales	$1.20M	SUM(Sales)
📦 Number of Items	8523	COUNT(Item Identifier)
⭐ Average Rating	3.92	AVERAGE(Rating)
📊 Average Sales	$141	AVERAGE(Sales)
📊 Visualizations Created
1️⃣ Outlet Establishment Trend (Area Chart)

Purpose:
Analyze how sales vary based on outlet establishment year.

X-Axis: Outlet Establishment Year
Y-Axis: Total Sales

Formula Used:

Total Sales = SUM('BlinkIT Grocery Data'[Sales])
2️⃣ Total Sales by Item Fat Content (Donut Chart)

Purpose:
Compare Low Fat vs Regular item contribution to total sales.

Fields Used:

Legend → Item Fat Content

Values → Total Sales

3️⃣ Total Sales by Item Type (Bar Chart)

Purpose:
Identify highest performing product categories.

Top Categories Observed:

Fruits

Snacks

Household

Frozen Foods

Dairy

Canned

Baking Goods

Health & Hygiene

Formula Used:

Total Sales = SUM(Sales)
4️⃣ Outlet Size Contribution (Donut Chart)

Purpose:
Analyze how outlet size affects sales.

Categories:

Small

Medium

High

5️⃣ Outlet Location Type (Bar Chart)

Purpose:
Compare sales across:

Tier 1

Tier 2

Tier 3

6️⃣ Outlet Type Performance Table (Matrix Table)

Purpose:
Compare different outlet types based on:

Total Sales

Number of Items

Average Rating

Average Sales

Outlet Types Analyzed:

Grocery Store

Supermarket Type1

Supermarket Type2

Supermarket Type3

🎛 Filters (Slicers Used)

Left panel contains dynamic filters:

Outlet Location Type

Outlet Size

Outlet Type

These slicers dynamically update all visuals.

🧮 DAX Measures Created
Total Sales = SUM('BlinkIT Grocery Data'[Sales])

Number of Items = COUNT('BlinkIT Grocery Data'[Item Identifier])

Average Sales = AVERAGE('BlinkIT Grocery Data'[Sales])

Average Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
🛠 Tools & Features Used

Power BI Desktop

DAX Calculations

Slicers

KPI Cards

Donut Chart

Bar Chart

Area Chart

Matrix Table

Data Modeling

Data Cleaning in Power Query

Conditional Formatting

Custom Color Theme (Yellow/Green – Blinkit Theme)

📊 Insights Derived

✔ Tier 3 outlets contribute highest sales
✔ Medium sized outlets generate majority revenue
✔ Fruits & Snacks are top-selling categories
✔ Low Fat items have slightly higher sales share
✔ Supermarket Type1 generates highest revenue
✔ Average rating across outlets is ~3.9

🚀 Skills Demonstrated

Data Cleaning & Transformation

DAX Measure Creation

Business KPI Development

Dashboard Designing

Data Visualization

Sales Performance Analysis

Retail Data Analytics

🎯 Business Impact

This dashboard helps:

Identify top-performing outlet types

Understand customer buying patterns

Optimize product category strategy

Improve outlet expansion planning

Increase revenue through data-driven decisions
