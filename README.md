# Pizza-Sales-Project-with-Power-BI-SQL  
## Project Overview  
In this pizza sales case study, we dive into the numbers behind the orders, examining key metrics like sales volume, revenue generation, and customer preferences. From identifying the most popular pizza types to understanding peak order times, this analysis provides crucial insights for better business decisions. The data not only reveals which pizzas are driving the highest revenue but also highlights trends in pizza sizes and category preferences, offering valuable takeaways for optimizing inventory, staffing, and menu offerings.  
## Business Objective  
- Evaluate overall sales and revenue performance.
- Identify top-performing and underperforming products.
- Analyze customer demand patterns across time.
- Understand the impact of pizza size and category on revenue.
- Provide insights to improve sales and operational efficiency.
## Tools & Technologies  
- SQL (MySQL) – Data extraction & analysis
- Power BI – Data visualization & dashboard creation
- Excel/CSV – Dataset
## Dataset Description  
The dataset includes:  
- Orders data (date, time, order ID)
- Pizza details (name, category, size)
- Order details (quantity, price)
## Data Processing & SQL Workflow  
### Key steps performed in SQL:  
- Data validation and consistency checks
- Joining multiple tables to create a unified dataset
- Aggregations for revenue and order metrics
- Time-based analysis (daily, monthly trends)
- Ranking and window functions to identify top products
### Key queries performed in SQL:
- Total revenue calculation
- Top 5 best-selling pizzas
- Revenue contribution by category and size
- Orders distribution by time (day)
- Monthly sales trends

  ## Power BI Workflow
After extracting insights using SQL, the dataset was loaded into Power BI for visualization.
Steps Followed
1. Connecting the Data
○ Imported the dataset into Power BI directly from the SQL database.
○ Verified data types (dates, floats, integers).
2. Transformations in Power Query
○ Created calculated columns such as Month Name and Day of Week for better
grouping.

Creating Measures

○ Used DAX measures to replicate SQL insights:
■ Total Revenue = SUM(total_price)
■ Avg Order Value = DIVIDE([Total Revenue],
DISTINCTCOUNT(order_id))
■ Total Orders = DISTINCTCOUNT(order_id)
## Dashboard (Power BI)
An interactive dashboard was developed to present insights in a clear and business-friendly format.
Key Features:  
- KPI Cards: Total Revenue, Total Orders, Average Order Value
- Sales breakdown by category and pizza size
- Top & bottom-performing pizzas
- Time-series analysis (daily & monthly trends) 
👉 (Include dashboard screenshots or GIFs here for stronger impact)
## Key Insights & Findings
•	A small subset of pizzas contributes disproportionately to total revenue (Pareto effect) 
•	Large-sized pizzas generate the highest revenue share 
•	Peak sales occur during evening hours, indicating strong dinner demand 
•	Certain categories consistently outperform others, suggesting opportunities for menu optimization 
•	Seasonal or monthly trends indicate fluctuations that can inform promotions and inventory planning 
•  The Classic category generates the highest revenue 
•  Large size pizzas contribute the most to sales 
•  Peak order times are in the evening hours 
•	•  A few top pizzas drive a significant portion of revenue


## Business Impact
This analysis can help stakeholders:
•	Optimize menu offerings by focusing on high-performing items 
•	Improve inventory and staffing based on demand patterns 
•	Design targeted promotions during low-sales periods 
•	Increase revenue through data-backed pricing and bundling strategies 


Project Workflow
1.	Data Collection & Understanding 
2.	Data Cleaning & Transformation (SQL) 
3.	Exploratory Data Analysis (SQL) 
4.	Data Modeling (Power BI) 
5.	Dashboard Development 
6.	Insight Generation & Storytelling 


Key Skills Demonstrated
•	Advanced SQL (joins, aggregations, window functions) 
•	Data modeling and relational schema understanding 
•	Data visualization and dashboard design (Power BI) 
•	Business insight generation and storytelling 
•	Analytical thinking and problem-solving
•	Improved SQL skills (joins, aggregations, CTEs) 
•	Hands-on experience with Power BI dashboards 
•	Learned how to convert raw data into business insights 


