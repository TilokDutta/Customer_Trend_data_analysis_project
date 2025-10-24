🧠 Customer Shopping Behavior – Data Analytics Project

📌 Overview
This project focuses on analyzing customer shopping behavior to uncover insights about purchase patterns, product performance, and customer segments. The workflow covers the full data analytics pipeline — from data cleaning and exploration to SQL-based analysis, dashboard visualization, and report presentation.
The goal is to translate raw data into actionable business insights that support decision-making in sales, marketing, and customer engagement.

📂 Dataset
Name: customer_shopping_behavior.csv
Description: Contains transaction-level data such as customer ID, purchase amount, product category, shipping type, review rating, and discount details.
Key Columns:
customer_id – Unique identifier for each customer
item_purchased – Product name or category
purchase_amount – Total amount spent
review_rating – Product rating (1–5 scale)
shipping_type – Delivery mode (Standard / Express)
discount_applied – Whether a discount was used
previous_purchases – Number of past purchases

🛠️ Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn) – Data loading, cleaning, and exploratory data analysis (EDA)
SQL (PostgreSQL / MySQL / SQL Server) – Querying and extracting business insights
Power BI – Interactive dashboard creation and visualization
Gamma App – Presentation deck generation
Jupyter Notebook / VS Code – Code development and documentation

🔍 Project Steps
1) Data Loading
  -Imported CSV dataset into Python.
  -Checked data types, missing values, and duplicates.
2) Data Cleaning
  -Handled missing values using mean/median imputation.
  -Standardized column names and corrected inconsistent entries.
  -Removed or adjusted outliers for numeric columns.
3) Exploratory Data Analysis (EDA)
  -Visualized purchase trends, ratings, and category performance.
  -Identified top-selling categories and customer segments.
  -Correlation analysis between review ratings and purchase amount.
4) SQL Analysis
  -Connected dataset to PostgreSQL/MySQL.
  -Executed analytical queries to answer business questions.
5) Power BI Dashboard
  -Designed visuals for KPIs like total revenue, average rating, top products, and customer type distribution.
  -Created interactive filters for category, region, and shipping type.
6) Reporting & Presentation
  -Summarized findings in a detailed analytical report.
  -Created a clean, professional presentation using Gamma App to communicate results effectively.

📊 Dashboard Overview
The Power BI Dashboard highlights:
Total Sales & Average Purchase Value
Top 5 Products by Rating and Sales
Customer Segmentation by Loyalty
Discount Utilization Impact
Shipping Type vs. Purchase Trends

📈 Results & Insights
i) Returning customers accounted for the highest average purchase value.
ii) Express shipping customers spent ~20% more on average than standard shipping users.
iii) Top-rated products correlated strongly with repeat purchases.
iv) Discounts influenced short-term sales but not long-term loyalty.

⚙️ How to Run
Clone the repository:
git clone https://github.com/yourusername/customer-shopping-analysis.git

Navigate to the project folder:
cd customer-shopping-analysis

Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

Install dependencies:
pip install -r requirements.txt

Open the Jupyter Notebook:
jupyter notebook

Run SQL queries using PostgreSQL/MySQL connection.

Open the Power BI file (dashboard.pbix) to view the visualizations.

📜 Deliverables

EDA Notebook: customer_analysis.ipynb

SQL Queries: analysis_queries.sql

Power BI Dashboard: customer_dashboard.pbix 

Presentation link  : https://gamma.app/docs/Customer-Shopping-Behavior-Analysis-l8yagq7ctri9ktw?mode=present#card-1djkm1nkbzr8ln9

Report: customer_behavior_report.pdf

Presentation: customer_insights_presentation.gamma
