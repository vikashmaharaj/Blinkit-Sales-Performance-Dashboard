# 🛒 Blinkit Sales & Operations Analysis Dashboard  

> A Complete End-to-End Data Analytics Project using **Power BI**  

---

## 📌 Project Overview  

This project is a comprehensive **Business Intelligence Dashboard** built using **Power BI** to analyze sales, outlet performance, and product trends for **:contentReference[oaicite:0]{index=0}**.  

The dashboard provides actionable insights into:

- 📊 Sales Performance  
- 🏪 Outlet Analysis  
- 📦 Product Category Trends  
- ⭐ Customer Ratings  
- 💰 Revenue Distribution  
- 📍 Location-Based Performance  

This project demonstrates strong skills in **Data Cleaning, Data Modeling, DAX, Data Visualization, and Business Insight Generation**.

---

# 🎯 Business Objective  

The main objective of this project is to:

- Analyze overall sales performance.
- Identify high-performing outlets.
- Evaluate product category contribution.
- Understand customer rating patterns.
- Provide business insights for data-driven decisions.

---

# 🗂️ Dataset Description  

The dataset includes the following key fields:

- `Item Fat Content`
- `Item Identifier`
- `Item Type`
- `Outlet Establishment Year`
- `Outlet Identifier`
- `Outlet Location Type`
- `Outlet Size`
- `Outlet Type`
- `Item Visibility`
- `Item Weight`
- `Sales`
- `Rating`

---

# 🛠️ Tools & Technologies Used  

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard Creation & Visualization |
| **Power Query** | Data Cleaning & Transformation |
| **DAX (Data Analysis Expressions)** | KPI Calculations & Measures |
| **Excel / CSV Dataset** | Data Source |

---

# 🧹 Data Cleaning & Preparation  

✔ Removed missing values  
✔ Handled null values in Item Weight  
✔ Standardized categorical columns  
✔ Corrected inconsistent labels (Low Fat, LF, etc.)  
✔ Created calculated columns & measures  
✔ Data type corrections  

---

# 📊 Key Performance Indicators (KPIs)  

- 💰 **Total Sales**
- 📦 **Total Items Sold**
- ⭐ **Average Rating**
- 🏪 **Number of Outlets**
- 📍 Sales by Location Type
- 🥫 Sales by Item Type
- 🏬 Sales by Outlet Size
- 🕒 Sales by Establishment Year

---

# 📈 Dashboard Features  

## 1️⃣ Overall Sales Analysis
- Total Revenue Overview
- Sales by Item Type
- Fat Content Contribution
- Year-wise Sales Trend

## 2️⃣ Outlet Performance Analysis
- Outlet Type Comparison
- Outlet Size Performance
- Location Tier Analysis
- Establishment Year Impact

## 3️⃣ Product Insights
- Top Performing Categories
- Low Performing Categories
- Visibility Impact on Sales
- Rating vs Sales Comparison

---

# 🧠 DAX Measures Used  

Examples of important measures:

```DAX
Total Sales = SUM('Blinkit'[Sales])

Average Rating = AVERAGE('Blinkit'[Rating])

Total Items = COUNT('Blinkit'[Item Identifier])
