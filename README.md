# 📊 SQL Analysis for Business Insights

This repository contains SQL queries designed for various business analysis scenarios, including product price analysis, sales performance, and logistical performance reviews. The queries aim to support decision-making processes for different departments within a company.

## 🗂️ Project Overview

This project includes four main analyses:

1. **Product Price Analysis**
2. **Finance Price Change Analysis**
3. **Logistics Performance Analysis**
4. **Sales KPI Analysis**

---

## 🔍 Detailed Analysis

### 1. Product Price Analysis

The **Product Team** wants an annual review of the company's pricing strategy. The analysis provides:

- Product names and unit prices
- The price range category each product falls into
- The number of products within each price range

**Key Query Features:**
- Uses a `CASE` statement for segmenting products into defined price ranges.
- Utilizes window functions for counting products per price range.

### 2. Finance Price Change Analysis

The **Finance Team** is interested in identifying which products have experienced a price increase over time.

**Key Query Features:**
- Uses `LEAD` and `LAG` window functions to compare current and previous unit prices.
- Calculates the percentage increase in unit prices.
- Filters results to only show products with price changes.

### 3. Logistics Performance Analysis

The **Logistics Team** needs a historical performance review for the year 1998, focusing on the efficiency of their operations in different countries.

**Key Query Features:**
- Calculates the average number of days between the order date and the shipment date.
- Aggregates the total number of orders by country.
- Filters data for the year 1998.

### 4. Sales KPI Analysis

The **Sales Team** wants to evaluate employee performance using a comprehensive list of KPIs.

**Key Query Features:**
- Includes full names and job titles of employees.
- Calculates total sales (excluding and including discounts).
- Provides average amounts per entry and per order.
- Determines the total discount amount and overall discount percentage.
- Ranks employees based on total sales including discounts.

---

## 📑 Technologies Used

- **Database:** PostgreSQL
- **SQL Concepts:** Window functions, CTEs, Aggregations, JOINs, CASE statements

---

## 📈 Results and Insights

This analysis provides valuable insights to help various departments make informed decisions:

- **Product Team:** Understands product pricing distribution and identifies pricing trends.
- **Finance Team:** Gains visibility into products with increasing unit prices.
- **Logistics Team:** Assesses performance efficiency by country and identifies areas for improvement.
- **Sales Team:** Evaluates employee performance using key metrics and KPIs.

---

## 🚀 How to Run the Queries

1. Ensure you have access to a PostgreSQL database with relevant tables (`products`, `order_details`, `orders`, `employees`).
2. Copy and paste each SQL script into your SQL editor.
3. Execute the queries in the specified order.

---

## 📬 Contact

For any questions or feedback, please reach out:

- **GitHub Profile:** [DilaKong](#)
- **Email:** [dilaturkan96@gmail.com]

---

💡 **Contributions:** Feel free to fork this repository and submit pull requests if you have any improvements or suggestions.

---

📝 **License:** This project is open-source and available under the [MIT License](LICENSE).
