A portfolio project demonstrating data analysis and visualization skills for a Sourcing Analyst role. This project simulates procurement data for H&R Block's tax season, focusing on spend analysis, supplier performance, and contract management.

📊 Project Overview
The dashboard provides insights into:

Total spend, active contract value, and potential savings

Spend breakdown by category and cost center

Monthly spending trends

Active contracts with savings targets

Interactive filtering by category and date

This project showcases proficiency in SQL, data modeling, and Power BI – key skills for the Sourcing Analyst position.

🗃️ Data Structure
The data is stored in a SQLite database (HRBlock_Sourcing.db) with four related tables:

Suppliers – Supplier details (name, category, risk level, diversity status)

Contracts – Contract information (value, savings target, active status)

PurchaseOrders – Individual purchase orders (dates, amounts, delivery status)

Spend – Detailed transactional spend data

Relationships are built between tables to enable cross-filtering and accurate metrics.

📈 Dashboard Features
Page 1: Executive Summary
KPI Cards: Total Spend, Active Contract Value, Potential Savings, Delayed Orders, Total Purchase Orders

Donut Chart: Spend by Category

Line Chart: Monthly Spend Trend

Bar Chart: Spend by Cost Center

Table: Active Contracts List (with savings targets formatted as percentages)

Slicers: Category and Date range filters

🛠️ Tools Used
SQLite – Database creation and data population

Power BI – Data modeling, DAX calculations, and interactive dashboard design

🚀 How to Use
Download the HRBlock_Sourcing.db SQLite database file.

Download the HRBlock_Sourcing_Dashboard.pbix Power BI file.

Open the .pbix file in Power BI Desktop.

If prompted, reconnect to the SQLite database by pointing to the downloaded .db file.

Explore the dashboard and interact with slicers.
