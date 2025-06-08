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

## 📊 Analysis Breakdown

### 🛍️ Product Analysis

* Count of unique product lines
* Most popular product line and payment method
* Product lines with highest revenue, VAT, and COGS
* Product performance categorized into `Good` or `Bad` based on average sales
* Product preference by **gender** and **branch**
* Average rating per product line

### 💵 Sales Analysis

* Total monthly revenue and best-performing months
* Product sales by **time of day** and **weekday**
* Sales and VAT distribution across **cities**
* Revenue breakdown by **customer type**

### 👥 Customer Analysis

* Customer segmentation (types and payment methods)
* Highest-spending customer group
* Gender distribution overall and per branch
* Ratings distribution by **time of day** and **day of week**

---

## ❓ Key Business Questions Addressed

* Which city generates the most revenue?
* Which product line performs best?
* Which time/day sees the highest sales volume?
* What is the gender profile of Walmart customers?
* Which customer type is most profitable?
* How does sales performance vary across months and branches?

---

## 🛠️ Tech Stack

| Layer            | Tools/Technologies            |
| ---------------- | ----------------------------- |
| 📥 Data Storage  | MySQL                         |
| 🧹 Data Cleaning | SQL (via queries and scripts) |
| 📈 Data Analysis | SQL                           |
| 📊 Visualization | Excel / Power BI (optional)   |

---

## 📌 Conclusion

This SQL-driven project offers a complete breakdown of Walmart's retail performance across branches, products, and customer segments. The insights extracted can guide **marketing, sales strategy, inventory planning**, and **customer retention initiatives**.

---

Let me know if you want a **Power BI or visualization-ready section** added as well!


