# sales-analysis--power-bi
🔹 README File for Project
Sales Analysis Dashboard 🚀

Capstone Project using MySQL, Excel & Power BI

📌 Project Overview

The goal of this project was to unlock sales insights that were not easily visible before, support decision-making, and automate reporting to reduce manual data gathering efforts by the sales and analytics team.

The end result is an interactive, automated Power BI dashboard that provides real-time visibility into sales performance, customer behavior, and product trends.

🎯 Objectives

Provide data-driven sales insights to the Sales, Marketing, and Customer Service teams.

Eliminate manual reporting by automating dashboards.

Enable faster decisions with real-time updates.

Deliver measurable outcomes:

10% cost savings in sales spend.

20% time savings for analysts (less manual work).

👥 Stakeholders

Sales Director

Marketing Team

Customer Service Team

Data Analytics Team

IT Team

🛠 Tools & Technologies

MySQL Workbench → Database import & storage

ODBC Connector → Connection between MySQL & Power BI

Power Query → Data cleaning & transformation

DAX → Custom measures (Revenue, Sales Qty, KPIs)

Power BI Desktop & Service → Dashboard creation & publishing

Excel → Initial checks & validations

🗂 Data Model

Imported five tables from MySQL:

Customers

Date

Markets

Products

Transactions

Relationships established in Power BI model view for one integrated dataset.

🧹 Data Cleaning

Removed blank values in Markets table.

Filtered out invalid transactions where sales_amount <= 0.

Converted multiple currencies into INR:

if [currency] = "USD" then [sales_amount] * 75 else [sales_amount]


Replaced all currencies with INR for consistency.

Standardized data types for calculation.

📊 Dashboard Features

The Sales Analysis Dashboard provides multiple layers of insights:

🔹 Key Metrics (KPI Cards)

Total Revenue (INR)

Total Sales Quantity

Average Order Value

% Growth vs Previous Period

🔹 Revenue Analysis

Revenue by Year/Month – with slicers for time-based analysis.

Revenue by Region/Market – compare performance across geographies.

Revenue by Product – top 10 products driving sales.

🔹 Customer Insights

Top Customers by Spend – who contributes most to revenue.

Customer Segmentation – retention vs new customers.

🔹 Trend Analysis

Monthly Revenue Trends – line chart with seasonality detection.

Sales Quantity Distribution – bar chart by product/region.

🔹 Operational Insights

Highlighted low-performing markets/products.

Identified garbage/duplicate data trends in raw inputs.

Enabled drill-through for transaction-level details.

🔹 Mobile Layout

Optimized dashboard for Power BI Mobile App, ensuring access anytime, anywhere.

📈 Findings & Insights (from dashboard)

Revenue showed consistent growth YOY, but some months had sharp dips (possible seasonal effect).

Top 5 products contributed ~60–70% of total revenue, highlighting concentration risk.

Certain markets underperformed, offering opportunities for cost savings.

Analysts now spend less time on reporting and more on decision-support activities.

✅ Success Criteria Achieved

Automated dashboard reduces manual reporting.

Faster decisions with self-service analytics.

Potential 10% cost savings and 40% analyst time savings.

🌐 Publishing

Dashboard published on Power BI Service (app.powerbi.com).
