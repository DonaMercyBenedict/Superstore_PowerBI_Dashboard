# 📊 Superstore Sales Analysis Dashboard | Power BI

## 📌 Project Overview

This project presents an interactive **Superstore Sales Analysis Dashboard** built using **Microsoft Power BI**. The dashboard provides meaningful insights into sales performance, profitability, customer behavior, and regional trends to support data-driven business decisions.

The goal of this project is to transform raw sales data into an interactive and visually appealing report that helps identify key business opportunities and performance gaps.

---

## 🎯 Business Objectives

The dashboard aims to answer important business questions:

- How are sales and profits performing over time?
- Which product categories and sub-categories generate the most revenue?
- Which regions and states contribute the highest sales?
- Who are the most valuable customers?
- Which products are profitable or causing losses?
- What trends can help improve business strategies?

---

## 🛠️ Tools & Technologies Used

- **Microsoft Power BI** – Data visualization and dashboard development
- **Power Query** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – Creating calculated measures and KPIs
- **Excel / CSV Dataset** – Data source

---

## 📂 Dataset

The project uses the **Superstore Sales Dataset**, containing information about:

- Orders
- Customers
- Products
- Categories
- Sales
- Profit
- Discounts
- Shipping details

Key fields include:

- Order Date
- Customer Name
- Region
- Category
- Sub-Category
- Sales
- Profit
- Quantity
- Discount

---

## 📊 Dashboard Features

### 🔹 Executive Summary
- Total Sales
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin

### 🔹 Sales Analysis
- Sales trends over time
- Category and sub-category performance
- Regional sales comparison
- Top-selling products

### 🔹 Profitability Analysis
- Most profitable products
- Loss-making products
- Discount impact on profit
- Profit distribution by region

### 🔹 Customer Analysis
- Top customers by sales
- Customer purchasing patterns
- Customer contribution analysis

---

## 📸 Dashboard Preview

![Superstore Power BI Dashboard](Dashboard_Screenshot.png)

---

## 📈 Key Insights

Some insights discovered from the analysis:

- Identified the highest-performing product categories and regions.
- Analyzed the relationship between discounts and profitability.
- Highlighted products generating high sales but lower profit margins.
- Found customer segments contributing significantly to revenue.
- Evaluated yearly and monthly sales trends.

---

## 🧮 DAX Measures Created

Examples of calculated measures:

```DAX
Total Sales = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Profit Margin = 
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)

Total Orders = DISTINCTCOUNT(Superstore[Order ID])
