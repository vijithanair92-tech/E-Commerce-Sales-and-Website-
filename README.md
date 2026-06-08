# E-Commerce-Sales-and-Website-Conversion Analysis Using Python
This project focuses on analyzing the Maven Fuzzy Factory e-commerce dataset using Python. The analysis combines sales data, website traffic data, customer behavior data, and product information
Project Documentation
Project Title
E-Commerce Sales and Website Conversion Analysis Using Python
________________________________________
1. Project Overview
This project focuses on analysing the Maven Fuzzy Factory e-commerce dataset using Python. The analysis combines sales data, website traffic data, customer behaviour data, and product information to uncover business insights related to revenue growth, product performance, customer acquisition, conversion rates, and refunds.
The goal is to transform raw business data into actionable insights that can support data-driven decision-making and improve overall business performance.
________________________________________
2. Tools Used
3. 
•	Python – Data Analysis 
•	Pandas – Data Cleaning and Manipulation  
•	Matplotlib – Data Visualization 
•	Seaborn – Statistical Visualizations 
•	Plotly – Interactive Visualizations 
•	Jupyter Notebook – Analysis Environment 
________________________________________
3. Dataset
Source:
Maven Analytics – Fuzzy Factory Dataset
Description:
The project utilizes multiple related tables containing information about customer transactions, website activity, products, and refunds.
Main Tables:
# Website Sessions
Contains website visitor session information:
•	website_session_id 
•	created_at 
•	user_id 
•	utm_source 
•	utm_campaign 
•	device_type 
•	is_repeat_session 
# Orders
Contains customer order information:
•	order_id 
•	website_session_id 
•	user_id 
•	primary_product_id 
•	items_purchased 
•	price_usd 
•	cogs_usd 
# Order Items
Contains product-level order details:
•	order_item_id 
•	order_id 
•	product_id 
•	item_price_usd 
•	cogs_usd 
# Products
Contains product catalog information:
•	product_id 
•	product_name 
# Refunds
Contains refund information:
•	order_item_refund_id 
•	order_item_id 
•	refund_amount_usd 
________________________________________
4. Data Preparation
5. 
$ Data Cleaning

The following preprocessing steps were performed:
1.	Imported all datasets using Pandas. 
2.	Checked for missing values and duplicates. 
3.	Converted date columns into datetime format. 
4.	Extracted Year, Month, and Day from order dates. 
5.	Renamed merged columns for better readability. 
6.	Created derived metrics for analysis.
7.	
$ Feature Engineering

Created additional columns:

•	Year 
•	Month 
•	Day 
•	Conversion Rate 
•	Refund Metrics 
•	Revenue Metrics 
________________________________________
5. Steps Followed
6. 
1. Data Understanding
2. 
•	Examined all tables 
•	Understood relationships between tables 
•	Created a data mode

4. Data Cleaning
•	Removed inconsistencies 
•	Converted data types 
•	Handled duplicate records

6. Data Merging
Merged tables using:
•	order_id 
•	product_id 
•	website_session_id 
to create a comprehensive sales dataset.

8. Exploratory Data Analysis (EDA)
9. 
Univariate Analysis
•	Product distribution 
•	Traffic source distribution 
•	Visitor type distribution

Bivariate Analysis
•	Revenue by product 
•	Orders by traffic source 
•	Refunds by product 

Multivariate Analysis
•	Product performance over time 
•	Revenue trends 
•	Correlation analysis 

11. Interactive Visualizations
Created interactive charts using Plotly:
•	Monthly Revenue Trend 
•	Product Conversion Funnel 
•	Traffic Source Analysis 
•	Refund Analysis 
•	Product Performance Dashboard 
•	Visitor Distribution Analysis

13. Business Insight Generation
Analyzed patterns and translated findings into business recommendations.
________________________________________
6. Key Insights
7. 
Revenue Trend
•	Revenue increased significantly during the final months of the year. 
•	November and December recorded the highest sales performance. 
Product Performance
•	The Original Mr. Fuzzy emerged as the best-selling product. 
•	It generated more than four times the orders of any other product. 
Website Traffic
•	Gsearch was the largest traffic source. 
•	Search engine marketing was the primary acquisition channel. 
Customer Behavior
•	83% of visitors were new visitors. 
•	17% were repeat visitors. 
Conversion Performance
•	Product conversion performance varied significantly. 
•	Original Mr. Fuzzy showed the strongest customer demand. 
Refund Analysis
•	Refund activity differed across products. 
•	Monitoring refund trends can help improve customer satisfaction and product quality. 
Correlation Analysis
•	Items Purchased and Order Price showed a strong positive correlation. 
•	Higher basket sizes resulted in higher revenue generation. 
________________________________________
7. Visualizations
The project includes the following visualizations:
Revenue Analysis<img width="917" height="330" alt="image" src="https://github.com/user-attachments/assets/5f4ff9d4-f76e-48f0-a2c5-8c001cead4a0" />

•	Monthly Revenue Trend (Interactive Line Chart) 
Product Analysis
•	Product Revenue Contribution 
•	Monthly Orders by Product Heatmap 
•	Product Conversion Funnel 
Customer Analysis
•	New vs Repeat Visitor Distribution <img width="778" height="365" alt="image" src="https://github.com/user-attachments/assets/7bd92aa1-ec1f-4f9a-bff1-792071dbb790" />

•	Device Type Distribution 
Marketing Analysis
•	Traffic Source Distribution 
•	Conversion Rate by Traffic Source  
Refund Analysis <img width="900" height="294" alt="image" src="https://github.com/user-attachments/assets/1286a1ea-fc2f-4c73-9215-eaa5b5fdd779" />

Refund Rate by Product 


Statistical Analysis
•	Correlation Heatmap  <img width="678" height="291" alt="image" src="https://github.com/user-attachments/assets/aab36481-317a-4d82-be77-7eb7c5329e62" />

________________________________________
8. Files Included
website_sessions.csv
orders.csv
order_items.csv
products.csv
order_item_refunds.csv
sales_analysis.ipynb
README.md
________________________________________
9. How to Use
Prerequisites
Install required libraries:
pip install pandas numpy matplotlib seaborn plotly
Running the Project
1.	Open sales_analysis.ipynb using Jupyter Notebook or JupyterLab. 
2.	Run the notebook sequentially. 
3.	Explore the visualizations and insights. 
4.	Modify the analysis to generate additional business insights. 
________________________________________
10. Conclusion
This project demonstrates how Python-based data analytics techniques can be used to analyse e-commerce business performance. By integrating sales, website traffic, customer behaviour, and product data, valuable insights were generated regarding revenue growth, customer acquisition, product performance, and conversion optimization.
The findings provide actionable recommendations that can help improve marketing effectiveness, customer retention, product strategy, and overall business growth.
________________________________________
Author
Vijitha V Nair
Data Analytics Project using Python, Pandas, Seaborn, Matplotlib, and Plotly
Dataset: Maven Fuzzy Factory E-Commerce Dataset
