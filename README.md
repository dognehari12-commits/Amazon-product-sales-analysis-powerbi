🚀 Amazon Sales Analysis Dashboard

📌 Project Overview

This project focuses on analyzing Amazon product sales data to extract meaningful insights using Power BI. 

The goal is to understand sales performance, product demand, and customer engagement through interactive dashboards.

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

Excel (Data Cleaning & Preparation

Power BI (Data Visualization & Dashboard)

DAX (Calculations & Measures)

📂 Datasets

- <a href="https://docs.google.com/spreadsheets/d/13kn4oOwsl_JyOFjx7gC4wXveOxfW_cgG/edit?gid=621652416#gid=621652416">Dataset</a>

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


<img width="1324" height="741" alt="Screenshot 2026-03-24 045006" src="https://github.com/user-attachments/assets/010c903c-82fb-4a9c-b70c-ba196fa20853" />

<img width="1327" height="744" alt="Screenshot 2026-03-24 045204" src="https://github.com/user-attachments/assets/e99c3d83-943d-4d21-bd22-61bfd89c2698" />

<img width="1325" height="742" alt="Screenshot 2026-03-24 045307" src="https://github.com/user-attachments/assets/4e977abe-4784-45d4-9b38-4e3391d338bd" />



⚙️ Project Workflow

Data Collection

Data Cleaning & Transformation

Data Modeling in Power BI

DAX Calculations

Dashboard Creation

Deployment

🗂️ Project Structure


<img width="1536" height="1024" alt="Project directory structure diagram (1)" src="https://github.com/user-attachments/assets/77b1c548-af81-491c-8384-b0082885f490" />

    


    
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
