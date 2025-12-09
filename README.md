📊 Customer Behaviour Analytics Project

🔍 Overview

This project focuses on analysing customer behaviour to uncover purchase patterns, segment customers, and identify business opportunities. The workflow includes data loading in Python, data cleaning, exploratory data analysis (EDA), SQL-based querying, Power BI dashboard development, and presentation creation. The objective is to transform raw transactional data into actionable insights for data-driven decision-making.

📂 Dataset

Source: CSV/Excel transactional dataset

Typical columns: CustomerID, Age, Gender, Product, Quantity, Amount, Date, City, etc.

Used for segmentation, trend analysis, EDA, and dashboard visualisation

🛠️ Tools & Technologies

Programming & Analysis: Python (Pandas, NumPy, Matplotlib, Seaborn)
Databases: PostgreSQL / MySQL / SQL Server
Data Visualization: Power BI
Presentation: Gamma App
Environment: Jupyter Notebook / VS Code

🧪 Project Workflow
1. Data Loading (Python)

Loaded dataset using Pandas

Inspected structure, datatypes, missing values, and quality issues

2. Data Cleaning

Handled null values and duplicates

Normalised formats and datatypes (date, numerical fields)

Feature engineering: total spend, visit frequency, recency metrics

3. Exploratory Data Analysis (EDA)

Univariate and bivariate analysis

Trend exploration (monthly sales, product performance, demographic distribution)

Correlation and distribution studies

4. SQL Querying

Executed analytical queries on PostgreSQL/MySQL/SQL Server to:

Segment customers using behavioural metrics

Aggregate sales revenue and order counts

Identify high-value customers (RFM indicators)

Evaluate product/category performance

Generate retention and churn insights

5. Power BI Dashboard

Developed an interactive dashboard including:

Customer segmentation and demographic insights

Sales trends, AOV, repeat purchase behaviour

Product/category revenue breakdown

Geographic insights and KPI cards

6. Report & Presentation

Summarised key findings and insights

Highlighted business implications and improvement opportunities

Created a clean, professional PPT using Gamma for project communication

📈 Key Results & Insights

Identified high-value customer segments driving majority of revenue

Revealed repeat-purchase patterns and retention trends

Highlighted top and bottom product categories

Provided data-driven recommendations for targeted marketing and customer engagement

▶️ How to Run the Project
Python
pip install -r requirements.txt
python analysis.py

SQL

Import dataset into chosen SQL database

Run queries from queries.sql

Power BI

Open dashboard.pbix

Refresh dataset connections for updated visuals

Presentation

Open presentation.gamma (Gamma export)

Review or customise slides if needed

📌 Project Structure
├── data/
├── notebooks/
├── scripts/
├── sql/
├── dashboard/
├── reports/
└── README.md

💡 Conclusion

This project demonstrates an end-to-end data analytics workflow, combining Python, SQL, and Power BI to deliver clear, actionable business insights from raw customer data. It showcases skills in data preparation, analytical thinking, visual storytelling, and professional reporting—reflecting real-world industry standards.
