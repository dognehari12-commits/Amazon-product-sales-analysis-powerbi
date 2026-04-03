🚀 Amazon Sales Analysis Dashboard
📌 Project Overview

This project focuses on analyzing Amazon product sales data to extract meaningful insights using Power BI. The goal is to understand sales performance, product demand, and customer engagement through interactive dashboards.

🎯 Problem Statement

With a large volume of products sold on Amazon, it becomes difficult to:

Track overall sales performance
Identify high-performing product categories
Understand customer purchasing behavior
Detect seasonal sales trends
💡 Proposed Solution

The solution involves building an interactive dashboard that:

Analyzes sales data
Tracks product performance
Evaluates customer engagement
Supports data-driven decision-making
🛠️ Tech Stack
Excel (Data Cleaning & Preparation)
Power BI (Data Visualization & Dashboard)
DAX (Calculations & Measures)

📂 Datasets

- <a href="https://docs.google.com/spreadsheets/d/13kn4oOwsl_JyOFjx7gC4wXveOxfW_cgG/edit?gid=621652416#gid=621652416">Dataset</a>



➕ Additional Derived Columns:
Month
Week Number
Quarter
Year
🧹 Data Preprocessing Steps
Handling missing values
Removing duplicates
Formatting date columns
Creating calculated fields:
YTD Sales
QTD Sales
Total Products Sold
Total Reviews
📊 Key Metrics (DAX Measures)
YTD Sales = TOTALYTD(SUM(Sales[Sales Amount]), Sales[Date])

QTD Sales = TOTALQTD(SUM(Sales[Sales Amount]), Sales[Date])

Total Products Sold = SUM(Sales[Products Sold])

Total Reviews = SUM(Sales[Reviews])
📈 Dashboard Features
🔹 KPI Cards
YTD Sales
QTD Sales
Total Products Sold
Total Reviews
🔹 Visualizations
Monthly Sales Trend 📊
Weekly Sales Trend 📉
Sales by Product Category 📦
Top 5 Products by Sales 🏆
Top 5 Products by Reviews ⭐
🔹 Filters (Slicers)
Product Category
Quarter
🖼️ Dashboard Preview

👉 (Yaha image paste kare)

![Dashboard Screenshot](images/dashboard.png)
⚙️ Project Workflow
Data Collection
Data Cleaning & Transformation
Data Modeling in Power BI
DAX Calculations
Dashboard Creation
Deployment
🗂️ Project Structure
Amazon-Sales-Analysis/
│
├── data/
│   └── amazon_sales_data.xlsx
│
├── dashboard/
│   └── Amazon_Sales_Dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── presentation/
    └── project_presentation.pdf
🚀 Deployment
Dashboard published on Power BI Service
Accessible via web/mobile
Interactive and user-friendly

👉 (Yaha Power BI link add karna)

📊 Results & Insights
Identified top-performing products and categories
Observed seasonal sales patterns
Analyzed customer engagement via reviews
Improved decision-making using data
✅ Conclusion

The dashboard provides:

Clear visibility into sales performance
Insights into customer behavior
Data-driven decision support
🔮 Future Scope
Real-time data integration
Machine learning for sales prediction
Customer segmentation analysis
Mobile dashboard optimization
Automated alerts & notifications
🔗 References
Dataset: (Add your Google Sheet link)
Dashboard Video: (Add video link)
🙌 Author

Harivansh Dogne

📧 dogne.hari12@gmail.com
