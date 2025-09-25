📊 Retail Sales Dashboard
🔹 Project Overview

This project is a Retail Sales Dashboard built in Tableau.
It provides insights into sales, profit, and performance across categories, sub-categories, and regions using an interactive dashboard.

The dataset is a synthetic Retail Sales Dataset (200 records).

🔹 Repository Structure
Retail-dashboard/
│
├── sample_retail_sales_dataset.csv       # Dataset
├── Retail Sales data.twbx                # Tableau packaged workbook
├── summary.pptx                          # Presentation (rename: remove space)
├── screenshots/                          # Dashboard screenshots
│   └── dashboard1.png
│   └── dashboard2.png
│   └── ...
└── README.md                             # Documentation

🔹 Dataset Description

File: sample_retail_sales_dataset.csv

Fields:

Order ID – unique order identifier

Order Date – date of the order

Customer ID – customer identifier

Region – North, South, East, West

Category – Electronics, Clothing, Groceries, Furniture

Sub-Category – product classification

Product Name – product description

Sales – revenue generated

Profit – profit earned

Quantity – units sold

Discount – discount applied

🔹 KPIs

The dashboard highlights:

Total Sales → SUM([Sales])

Total Profit → SUM([Profit])

Profit Margin % →

IF SUM([Sales]) = 0 THEN 0
ELSE SUM([Profit]) / SUM([Sales])
END


Average Order Value (AOV) →

SUM([Sales]) / COUNTD([Order ID])


Month-over-Month Growth % (since only one year is available) →

(SUM([Sales]) - LOOKUP(SUM([Sales]), -1)) / ABS(LOOKUP(SUM([Sales]), -1))

🔹 Visualizations

The dashboard includes:

📈 Sales Trend (Monthly Line Chart)

📊 Sales by Category (Bar Chart)

💹 Profit by Sub-Category (Bar Chart with Margin Coloring)

🌍 Sales by Region (Bar Chart)

🏆 Top N Products (Dynamic Parameter)

🔎 Sales vs Profit Scatter Plot

🎨 Monthly Sales Heatmap

📑 Detailed Order Table (Drill-down)

🔹 Interactivity

Filters: Region, Category, Sub-Category, Date

Parameters:

Select Measure → switch between Sales, Profit, Quantity

Top N Products → view top 5/10/15 products

Actions:

Filter actions (click → filter other charts)

Highlight actions (hover → emphasize related data)

🔹 Key Insights

Clothing & Electronics drive the highest sales.

Some sub-categories show negative profit (due to high discounts).

North & South regions lead in sales.

Top 10 products contribute significantly to total revenue.

MoM growth highlights small ups and downs across months.

🔹 How to Use

Clone this repo or download the dataset.

Open Retail Sales data.twbx
 in Tableau Desktop or Tableau Public.

Explore the interactive dashboard with filters and parameters.

🔹 Future Enhancements

Extend dataset to multiple years → enable YoY analysis.

Add customer segmentation (RFM analysis).

Connect to live data for real-time updates.

✍️ Author: Monisha B.N
