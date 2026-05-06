**NexCart Sales Data Analysis**
This is an end-to-end data analysis project I worked on using a real-world style e-commerce dataset from NexCart Analytics. The goal was to clean a messy dataset and then run SQL queries to pull out useful business insights.

**What the Project Covers:**
The project goes through three main stages:
Data Cleaning (Microsoft Excel)
The raw dataset came in with a lot of issues — inconsistent casing, broken email addresses, negative prices, wrong date formats, duplicate order IDs, impossible discount values, and ratings that were out of range. I worked through all of these in Excel using functions like PROPER, TRIM, SUBSTITUTE, ABS, DATEVALUE, and IF to fix or flag each issue. After cleaning, the dataset went from 500 rows down to 303 usable records.

**SQL Analysis (MySQL / phpMyAdmin)**
Once the data was clean, I imported it into MySQL and wrote 9 queries to answer key business questions around revenue, product performance, customer behavior, payment preferences, and the impact of discounting.

**Analysis Report**
All findings were documented in a structured Word report covering what each query returned and what it means for the business, along with recommendations based on the results.

**Tools Used**
•	Microsoft Excel: data cleaning
•	MySQL and phpMyAdmin:  SQL queries and analysis
•	Microsoft Word: report writing

**Files in This Repository**
File/Description
1.	nexcart_sales_raw: The original dataset before cleaning: 500 rows 
2.	nexcart_sales_cleaned.csv: The cleaned dataset used for analysis, 303 rows,
3.	nexcart_analysis.sql: All 9 SQL queries written for this project 
4.	NexCart_SQL_Analysis_Report.docx: Full analysis report with results and recommendations.

**Key Findings**
•	Total revenue from 303 valid orders came to $191,757.69
•	The South region generated the most revenue at $53,989.94, followed closely by Central at 51,161.49
•	Gaming Mouse was the bestselling product with 339 units sold
•	Over 41% of orders were either returned or cancelled, the biggest operational concern in the dataset
•	6 out of the top 10 cities by revenue are in Africa, showing strong market presence across the continent
•	Medium discounts of 11 to 20% drove the highest average order quantities, while higher discounts did not improve volumes

**What I Learned**
This project helped me get comfortable working with real dirty data rather than clean tutorial datasets. The cleaning process alone took a good amount of time and attention because there were multiple issues happening across different columns at the same time. Writing the SQL queries also helped me think about how to frame business questions in a way that the database can actually answer.

**Contact**:
Feel free to connect with me on LinkedIn if you want to discuss the project or anything data related.
www.linkedin.com/in/esther-omoshola-995a38379
