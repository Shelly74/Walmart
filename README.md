![Walmart Sales Project](Walmart%20Project.png)

# 🛍️ Walmart End-to-End Python-SQL Project
Absolutely! Here's a clean, professional, and well-structured **Markdown README** version for your **Walmart Sales Data Analysis (SQL Project)**. You can copy-paste this directly into your GitHub `README.md` file:

---

## 📌 Project Overview

This project involves analyzing **Walmart's sales data** to uncover insights about high-performing branches, top-selling product lines, customer behavior, and sales trends. The primary objective is to support data-driven sales optimization strategies.

The dataset is sourced from the **Kaggle Walmart Sales Forecasting Competition** and includes detailed transactional data from three Walmart branches located in **Mandalay**, **Yangon**, and **Naypyitaw**.

---

## 🎯 Project Goals

* Identify high-risk churn customers
* Understand behavioral and demographic sales drivers
* Analyze sales patterns and product performance
* Segment customer types and purchasing behavior
* Optimize sales strategy using data insights

---

## 📁 Dataset Description

The dataset includes **1,000 rows** and **17 columns**, representing transaction-level data. Here are the key fields:

| Column             | Description                         |
| ------------------ | ----------------------------------- |
| `invoice_id`       | Invoice number of the transaction   |
| `branch`           | Branch code where the sale occurred |
| `city`             | Location of the branch              |
| `customer_type`    | Member or Normal customer           |
| `gender`           | Gender of the customer              |
| `product_line`     | Category of product sold            |
| `unit_price`       | Price per unit of product           |
| `quantity`         | Quantity sold                       |
| `VAT`              | Value-added tax on the transaction  |
| `total`            | Total transaction amount (with tax) |
| `date`             | Transaction date                    |
| `time`             | Time of purchase                    |
| `payment`          | Payment amount                      |
| `cogs`             | Cost of Goods Sold                  |
| `gross_margin_pct` | Gross margin percentage             |
| `gross_income`     | Profit made from the transaction    |
| `rating`           | Customer rating for the transaction |

---

## 🧪 Approach & Methodology

### 1️⃣ Data Wrangling

* Checked for null values (none due to `NOT NULL` constraints)
* Created and populated SQL tables from cleaned dataset

### 2️⃣ Feature Engineering

Added new fields to enhance analysis:

* `time_of_day`: Categorized into **Morning**, **Afternoon**, **Evening**
* `day_name`: Extracted day of the week (Mon–Sun)
* `month_name`: Extracted month name for trend analysis

### 3️⃣ Exploratory Data Analysis (EDA)

Performed analysis using **SQL queries** to answer key business questions across product performance, customer behavior, and branch efficiency.

---
📊 Analysis Breakdown

🛍️ Product Analysis
How many distinct product lines are there in the dataset?

What is the most common payment method?

What is the most selling product line?

What is the total revenue by month?

Which month recorded the highest Cost of Goods Sold (COGS)?

Which product line generated the highest revenue?

Which city has the highest revenue?

Which product line incurred the highest VAT?

Retrieve each product line and add a column product_category, indicating 'Good' or 'Bad' based on whether its sales are above the average.

Which branch sold more products than the average number of products sold?

What is the most common product line by gender?

What is the average rating of each product line?

💵 Sales Analysis
Number of sales made in each time of the day per weekday

Identify the customer type that generates the highest revenue

Which city has the largest tax percent / VAT (Value Added Tax)?

Which customer type pays the most VAT?

👥 Customer Analysis
How many unique customer types does the data have?

How many unique payment methods does the data have?

Which is the most common customer type?

Which customer type buys the most?

What is the gender of most of the customers?

What is the gender distribution per branch?

Which time of the day do customers give most ratings?

Which time of the day do customers give most ratings per branch?

Which day of the week has the best average ratings?

Which day of the week has the best average ratings per branch?
