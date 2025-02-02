Consumer Goods Insights (SQL)

📌 Introduction

AtliQ Hardware (an imaginary company) is one of the leading electronic hardware producers in India. The company aims to expand its market presence and optimize operations by leveraging data-driven insights.

🏆 Problem Statement

The management at AtliQ Hardware realized they lack actionable insights to make fast and smart data-informed decisions. To address this, the company provided 10 ad hoc business requests requiring in-depth analysis and insight.

🎯 Project Objective: Ad Hoc Requests

1️⃣ APAC Market Presence

Identify the markets where the customer "AtliQ Exclusive" operates in the APAC region.

2️⃣ Unique Product Increase (2020 vs 2021)

Calculate the percentage increase of unique products in 2021 vs. 2020.

Output:

unique_products_2020

unique_products_2021

percentage_chg

3️⃣ Unique Products by Segment

Report the count of unique products for each segment, sorted in descending order by product count.

4️⃣ Segment-Wise Product Increase (2021 vs 2020)

Identify the segment with the largest increase in unique products from 2020 to 2021.

Output:

segment

product_count_2020

product_count_2021

difference

5️⃣ Highest and Lowest Manufacturing Cost

Find products with the highest and lowest manufacturing costs.

Output:

product_code

product

manufacturing_cost

6️⃣ Top 5 Customers by Discount

List the top 5 customers who received the highest average pre-invoice discount percentage in the Indian market for the fiscal year 2021.

Output:

customer_code

customer

average_discount_percentage

7️⃣ Gross Sales for AtliQ Exclusive

Generate a monthly report for "AtliQ Exclusive" showing gross sales in 2021.

Helps management understand high and low-performing months.

Output:

Month

Year

Gross_sales_amount

8️⃣ Highest Sold Quantity in 2020

Identify the quarter of 2020 with the maximum sold quantity.

Output:

Quarter

total_sold_quantity (sorted)

9️⃣ Top Sales Channel (2021)

Report the sales channel that contributed the most to gross sales in 2021 and its percentage contribution.

Output:

channel

gross_sales_mln

percentage

🔟 Top 3 Products by Division (2021)

List the top 3 products by total sold quantity for each division in 2021.

Output:

division

product_code

product

total_sold_quantity

rank_order

