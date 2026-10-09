# Customer Behavior Analysis

📌 Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions

🎯 Business Problem
A leading retail company wants to better understand its customers’ shopping behavior in order to improve sales, customer satisfaction, and long-term loyalty. The management is particularly interested in uncovering which factors, such as discounts, reviews, seasons, or payment preferences, drive consumer decisions and repeat purchases. 

📂 Dataset
-	Rows: 3,900 - Columns: 18 - Key Features: 
-	Customer demographics (Age, Gender, Location, Subscription Status) 
-	Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color) 
-	Shopping behavior (Discount Applied, Promo Code Used, Previous Purchases, Frequency of 
  Purchases, Review Rating, Shipping Type)
  Dataset link: [Add Dataset Link Here]

🛠️ Tools and Technologies

Python: Data cleaning and Exploratory Data Analysis.

MySQL: SQL queries and business analysis.

Power BI: Interactive dashboard development.

🔄 Project Workflow

1. Data Loading

- Imported the dataset into using Pandas.

- Examined the dataset structure, columns, and data types.

2. Data Cleaning And Exploratory Data Analysis (EDA) Using Python

- Handled missing values. Checked for null values and imputed missing values.
- Column Standardization: Renamed columns to snake case for better readability and documentation.
- Feature Engineering: Created new columns as per requirement.
- Data Consistency Check: Verified redundant columns and dropped them.
- Database Integration: Connected Python script to MySQL and loaded the cleaned DataFrame into the database for SQL analysis. 

4. SQL Analysis Using MySQL

- Loaded the cleaned dataset into MySQL.

- Used filtering, aggregation, grouping, CTE's and windows functions where applicable.

- Answered business questions using SQL queries.

5. Power BI Dashboard

- Imported the dataset into Power BI.

- Developed relevant KPIs and visualizations.

- Created an interactive dashboard to explore customer behavior and business performance.

6. Report Preparation

- Summarized the analysis and key findings.

- Documented important trends and business insights.

- Presented actionable recommendations based on the results.

📈 Dashboard

The Power BI dashboard provides a visual overview of customer behavior, purchasing patterns, and business performance.

Dashboard Screenshot:

[Add Dashboard Screenshot Here]

Power BI Dashboard: [Add Dashboard File or Link Here]

🔍 Key Insights

- Compared total generated  revenue by Gender.
- Identified 2.	High-Spending Discount Users
- Found top 5 products with the highest average review ratings.
- Compared Standard and Express shipping.
- Classified customers into New, Returning, and Loyal segments based on purchase history.
- Checked whether customers with >5 purchases are more likely to subscribe.       

💡 Business Recommendations
- Boost Subscriptions – Promote exclusive benefits for subscribers. 
 
- Customer Loyalty Programs – Reward repeat buyers to move them into the “Loyal” segment. 
 
- Review Discount Policy – Balance sales boosts with margin control. 
 
- Product Positioning – Highlight top-rated and best-selling products in campaigns. 
 
- Targeted Marketing – Focus efforts on high-revenue age groups and express-shipping users. 

📁 Project Structure

Customer-Behavior-Analysis/
│
├── data/
│   └── customer_behavior.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_queries.sql
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── images/
│   └── dashboard_screenshot.png
│
├── report/
│   └── customer_behavior_report.pdf
│
└── README.md

Note: Update the folder and file names to match your actual GitHub repository.

🚀 How to Run

Clone or download this repository.

Install Python and the required libraries:

pip install pandas numpy matplotlib seaborn sqlalchemy pymysql

Open the Jupyter Notebook and run the data cleaning and EDA steps.

Set up MySQL and create the required database and table.

Import the cleaned dataset into MySQL and execute the SQL queries.

Open the Power BI .pbix file in Power BI Desktop.

Refresh the data connections if required and explore the dashboard.

Review the project report for key findings and recommendations.

Prerequisites: Python, Jupyter Notebook, MySQL, and Power BI Desktop.


👤 Author

Shyama Mall
