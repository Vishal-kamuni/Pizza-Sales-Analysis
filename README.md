# 🍕 Pizza Sales Data Analysis

## 📌 Overview

This project is an exploratory data analysis (EDA) of pizza sales data. The dataset includes detailed transaction-level information for a pizza store, helping uncover patterns in sales performance, customer preferences, and popular pizza types over time.

The goal is to derive meaningful business insights that can help drive better decision-making in areas such as inventory management, sales strategy, and marketing.

## 🎯 Objectives

* Analyze overall sales trends and revenue generation.
* Identify the best and worst-selling pizza types.
* Understand time-based patterns in sales (daily, weekly, monthly).
* Discover the most popular pizza sizes and categories.
* Provide recommendations to optimize sales performance.

## 📂 Dataset Description

The dataset `pizza_sales.csv` includes the following columns:

| Column Name      | Description                                |
| ---------------- | ------------------------------------------ |
| `order_id`       | Unique identifier for each order           |
| `date`           | Date of the order                          |
| `time`           | Time of the order                          |
| `pizza_id`       | Unique identifier for the pizza            |
| `quantity`       | Quantity of pizza ordered                  |
| `unit_price`     | Price of a single unit of pizza            |
| `total_price`    | Total revenue from that pizza in the order |
| `pizza_size`     | Size of the pizza (S, M, L, XL, etc.)      |
| `pizza_category` | Category of pizza (Classic, Veggie, etc.)  |
| `pizza_name`     | Name of the pizza ordered                  |

## 🧠 Analysis Performed

* Data Cleaning and Preprocessing
* Daily and Monthly Sales Trends
* Top 10 Best and Worst-Selling Pizzas
* Sales by Pizza Category and Size
* Heatmaps of Hourly and Weekly Sales
* Revenue Contribution by Pizza Type

## 📊 Tools Used

* **Python**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Microsoft Excel**


## 📘 SQL Queries Document

The file `PIZZA SALES SQL QUERIES.docx` contains:

* Revenue and quantity analysis queries
* Best-selling and least-selling pizza queries
* Time-based breakdown (daily, monthly, hourly)
* Category and size-specific insights
* Join queries for building BI dashboards

## 📈 Key Insights

* Certain pizza types consistently outperform others in both quantity and revenue.
* Sales peak during weekends and dinner hours.
* Large and extra-large pizzas generate the most revenue.
* Veggie and Classic categories are more popular compared to others.
* Sales dip during early mornings and weekdays.

## ✅ Conclusion

This analysis provides a detailed understanding of customer behavior and product performance. It can be used to guide promotional strategies, adjust stock levels, and align operational planning with demand patterns.

## 📁 Repository Structure

```bash
📦pizza-sales-analysis/
 ┣ 📘 PIZZA SALES SQL QUERIES.docx
 ┣ 📊 pizza_sales.csv
 ┣ 📓 pizza_sales_analysis.ipynb
 ┗ 📄 README.md
 ┣ 📘Pizza_Sales.csv
