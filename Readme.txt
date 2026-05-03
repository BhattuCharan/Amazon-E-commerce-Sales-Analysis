🛒 Amazon E-commerce Sales & Operations Analysis
📌 Project Overview

This project analyzes Amazon-style e-commerce data to uncover sales trends, customer behavior, product performance, and operational efficiency. The goal is to transform raw transactional data into actionable business insights using Power BI.

The project focuses on identifying:

Revenue drivers
Customer purchasing patterns
Impact of product ratings on sales
Return behavior and risk areas
Category and brand performance
🎯 Objectives
Analyze sales performance from 2024–2026
Understand customer behavior across platforms and payment methods
Evaluate impact of product ratings on revenue
Identify high-return products and segments
Provide data-driven recommendations for business improvement
📊 Key KPIs
Total Sales
Total Orders
Return Rate %
Total Returns
Average Shipping Days
Average Discount %
Sales Previous Year (PY)
Year-over-Year Growth %
Average Product Rating
🧱 Data Modeling

A Star Schema was implemented for efficient analysis:

Fact Table:
Fact_Orders
Dimension Tables:
Dim_Date
Dim_Product
Dim_Customer
Dim_Seller

This structure ensures:

Better performance
Accurate filtering
Scalable analytics
🧹 Data Preparation
Cleaned and transformed data using Power Query
Created a custom Date table
Removed duplicates and standardized formats
Derived new columns:
Month Name
Month Number
Year
Year-Month
📈 Dashboard Overview
📊 Page 1: Sales & Customer Behavior Overview

Focus: Revenue, trends, and customer patterns

Visuals include:

YoY Monthly Sales Trend
Quarterly Sales by Category
Orders by Platform
Location-wise Sales
Brand-wise Average Rating
📊 Page 2: Product, Seller & Operational Insights

Focus: Returns, performance, and operational efficiency

Visuals include:

Orders by Payment Method
Monthly Shipping Performance
Top Subcategories by Orders
Sales by Seller Rating
Delivery Status Distribution
🔍 Key Insights
🟢 Positive Insights
Generated ₹9.94B in sales with 1M orders
Electronics dominates revenue and ratings
Mobile platform leads slightly in order volume
UPI is the most preferred payment method
Lenovo has the highest product rating
Strong demand concentrated in Delhi, Bangalore, Mumbai
⚠️ Challenges Identified
11.06% return rate (~116K returns)
Low-performing brands: HP, Sony, Apple, Adidas
Low-rated subcategories:
Kids, Skincare, Women, Haircare, Makeup
High return segments:
Kitchen, Decor, Headphones, Outdoor
Mobile category has 1.13× higher return probability
📉 Rating Impact on Sales
Ratings 3.3–4.3 → +2.11M sales increase
Ratings ≤3.1 → -2.03M sales drop

👉 Strong correlation between ratings and revenue

💡 Business Recommendations
Improve product quality and supplier standards
Optimize product descriptions and visuals
Reduce returns through better expectation setting
Focus on high-performing categories (Electronics)
Improve low-rated subcategories
Strengthen quality control for high-return products
Enhance mobile user experience
🛠️ Tools & Technologies
Power BI
Power Query
DAX (Data Analysis Expressions)
Excel (Data Preparation)


📌 Conclusion

This project demonstrates how data can be leveraged to:

Drive business decisions
Improve customer satisfaction
Optimize operations
Increase revenue efficiency

It showcases end-to-end skills in:

Data modeling
Data transformation
Visualization
Business storytelling