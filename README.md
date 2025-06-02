![Walmart Sales Project](Walmart%20Project.png)

# 🛍️ Walmart End-to-End Python-SQL Project

This project demonstrates a complete data analysis workflow on Walmart sales data using **Python** for data processing and **PostgreSQL** for SQL-based analytics. It highlights practical skills in data cleaning, transformation, and querying to derive meaningful business insights.

---

## ✅ Project Highlights

### 1. Data Cleaning & Loading (Using Python)

- Imported and worked with the **pandas** library.
- Read the sales dataset (CSV) after downloading and unzipping from Kaggle.
- Performed an initial exploration using:
  - `.shape`, `.info()`, `.describe()`, `.head()`
- Cleaned the dataset by:
  - **Dropping duplicates**
  - **Removing null values** (very few were present)
  - **Converting data types** to appropriate formats
- Engineered new features:
  - Created a **total_amount** column from existing `unit_price` × `quantity`.

---

### 2. Data Transfer & Analysis in PostgreSQL

- Loaded the cleaned dataset into a **PostgreSQL** database using SQLAlchemy.
- Structured a SQL table to store Walmart transactional data.
- Executed **multiple SQL queries** to extract insights related to:
  - Revenue trends
  - Product category performance
  - Customer behavior and payment methods

---

> This project serves as a strong demonstration of end-to-end data handling and analysis using Python and SQL — from data ingestion and transformation to SQL-driven decision-making.

