# Customer_behavior_analysis
Data analytics project showcasing customer behavior analysis using Python, SQL, and Power BI.

Customer Shopping Behavior Analysis
📌 Overview

This project focuses on analyzing customer shopping behavior to understand patterns in spending, subscriptions, product preferences, and discount usage. The workflow includes Python for data processing, SQL for deeper analysis, Power BI for visualization, and Gamma for final reporting.

📂 Dataset
Rows: 3,900
Columns: 18
Type: Customer purchase and behavioral data
Key Columns:
Age, Gender, Location, Category, Purchase Amount, Subscription Status, Discount Applied, Review Rating, Shipping Type, Season, Previous Purchases.

🛠 Tools
Purpose	Tool
Programming	Python
Database	PostgreSQL
Visualization	Power BI
Reporting	Gamma
Libraries Used	pandas, numpy, seaborn, matplotlib, sqlalchemy

📍 Steps
1️⃣ Load Dataset (Python)
Imported the CSV file into Python using pandas.
Verified structure, datatypes, and missing values.

2️⃣ EDA & Cleaning
Handled 37 missing review values using median imputation.
Removed redundant column (promo_code_used).
Created new helpful fields like age groups and purchase frequency.

3️⃣ Load to SQL
Connected Python to PostgreSQL and loaded the cleaned dataset.

4️⃣ SQL Analysis
Performed business-focused queries including:
Revenue by gender
Top products by rating
Discount users vs non-discount users
Subscribers vs non-subscribers
Product and category performance
Customer segmentation: New, Returning, Loyal

5️⃣ Dashboard
Built an interactive Power BI dashboard showing:
Total revenue and order count
Top product categories
Customer behavior trends
Subscription and discount impact
Shipping type comparison

6️⃣ Final Report
Created a clean business-friendly presentation in Gamma summarizing insights and recommendations.

📊 Results & Insights
✔ Subscribers spend more and purchase more often
✔ Discounts increase purchase count but reduce profitability
✔ Certain age groups contribute the highest revenue
✔ Top-rated items strongly influence purchase decisions
✔ Introducing loyalty rewards can increase repeat buyers

▶ How to Run
Install required packages
pip install pandas numpy seaborn matplotlib sqlalchemy psycopg2

Run the Notebook
python/eda_cleaning.ipynb

Run SQL queries
SQL/queries.sql

Open the Dashboard
dashboard/dashboard.pbix

View Final Presentation
report/presentation.gamma

🗂 Folder Structure
📁 Customer-Shopping-Behavior-Analysis
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── python/
│   └── eda_cleaning.ipynb
│
├── SQL/
│   └── queries.sql
│
├── dashboard/
│   └── dashboard.pbix
│
└── report/
    └── presentation.gamma

🚀 Future Improvements
Add predictive analytics (Customer churn, sales forecasting)
Deploy dashboard online
Automate ETL pipeline


