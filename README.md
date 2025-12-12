# Gift-Shop-Revenue-Order-Analysis-Dashboard
A complete end-to-end data analytics project analyzing the revenue and order performance of a Gift Shop for the year 2023, built using Microsoft Excel’s advanced capabilities including Power Query, Power Pivot, Data Modeling, and Interactive Dashboards.

This project demonstrates real business insights, clean ETL workflows, and professional dashboard design suitable for analysts and data enthusiasts.
🚀 Project Overview

This project focuses on analyzing key business metrics such as:

Revenue performance
Order patterns
Customer spending behavior
Product and occasion-wise performance
Delivery trends
City-level insights

Two fully interactive dashboards were developed:

1️⃣ Revenue Analysis Dashboard
2️⃣ Order Analysis Dashboard

These dashboards enable users to understand which products, cities, months, and occasions contribute the most to business growth.

🛠 Tools & Skills Used
Microsoft Excel
Power Query (ETL)
Power Pivot (Data Modeling)
PivotTables & PivotCharts
Interactive Slicers

Dashboard Design & Visualization

🧹 Data Preparation (ETL Workflow)
All transformations were done using Power Query, including:
Importing multiple Excel files from a folder
Creating derived columns:
Month Name (from Order_Date)
Order Hour & Delivery Hour
Revenue (Quantity × Price)
Average Delivery Time
Data quality checks (duplicates, invalid dates, missing values)

A Star Schema model was built in Power Pivot:

Fact Table: Orders
Dimension Tables: Customer, Product

Relationships:
Customer_ID → Orders
Product_ID → Orders

📈 Key Dashboard Insights
⭐ 1. Revenue Insights
Total Revenue: ₹13,33,246
Highest revenue occasions: Anniversary, Raksha Bandhan, Holi
Best-selling products:
Teddy Bear (Medium)
Kaju Katli Box (500g)
Motichoor Ladoo Box (500g)
Top revenue cities: Ghaziabad, Bareilly, Tirunelveli

⭐ 2. Order Insights
Total Orders: 1000
Peak months: February, March, August, November
Highest order occasions: Anniversary, Holi, Birthday
Male & Female customers show similar product preferences
Average Delivery Time: 5.53 days
Average Customer Spend: ₹1333

🔍 Combined Business Insights
Business is festival-driven → High seasonal demand
Same products dominate both revenue and order volume
Strong contribution from Tier-2/Tier-3 cities
Customer behavior is gender-neutral → unified marketing works well
Delivery time needs improvement to boost satisfaction
Few top customers contribute significantly → opportunity for loyalty programs

📌 Recommendations
Strengthen inventory during festival seasons
Launch loyalty programs for high-value customers
Improve delivery speed (current avg: 5.53 days)
Target high-performing cities with digital ads
Boost sales in low months via flash sales & combo offers
Promote top-performing products via bundles and offers



Screenshots:
<img width="4722" height="2267" alt="image" src="https://github.com/user-attachments/assets/1aff536c-8ea8-4dca-a014-9dce20d2090e" />

<img width="3463" height="2138" alt="image" src="https://github.com/user-attachments/assets/2023c500-afa0-41df-b5ad-ae542f4fbb49" />

## 🚀 Live Dashboard Preview  
📌 Click below to view the full PDF report:  
👉 [Revenue & Order Analysis Report](https://github.com/suyashutekar11/Gift-Shop-Revenue-Order-Analysis-Dashboard/blob/main/Report%20of%20Revenue%20%26%20Order%20Analysis%20Dashboard%20for%20a%20Gift%20Shop.pdf)


Conclusion
This project demonstrates a complete analytics workflow—from data extraction and transformation to interactive visualization. It highlights how Excel can be used as a powerful BI tool to reveal insights that support better inventory planning, marketing decisions, delivery optimization, and customer engagement.
