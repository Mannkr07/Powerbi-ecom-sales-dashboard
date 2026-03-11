# 📊 Ecommerce Sales Dashboard (Power BI)

## 📌 Project Overview

The **Ecommerce Sales Dashboard** is an interactive business intelligence project built using **Power BI**. The dashboard analyzes ecommerce sales data to provide insights into revenue, customer purchasing behavior, product performance, and payment trends.

The objective of this project is to transform raw transactional data into **clear and actionable insights** that help businesses understand their sales performance and identify opportunities for improvement.

The dashboard allows users to explore sales across **different states, product categories, time periods, and payment modes**, helping stakeholders make data-driven decisions.

---

# 🎯 Project Objectives

* Analyze overall ecommerce sales performance
* Identify the most profitable products and categories
* Understand customer purchasing behavior
* Monitor monthly profit trends
* Evaluate sales distribution across different states
* Analyze customer payment preferences

---

# 📊 Key Performance Indicators (KPIs)

The dashboard highlights the following important business metrics:

* **Total Sales Amount:** 161K
* **Total Quantity Sold:** 2008 units
* **Total Profit:** 26K
* **Average Order Value (AOV):** 44K

These KPIs provide a quick overview of the company’s performance.

---

# 📁 Dataset Description

This project uses two datasets:

## 1️⃣ Orders Dataset (`orders.csv`)

This dataset contains high-level order information including:

* Order ID
* Order Date
* State
* Customer Name

It helps track **where and when orders were placed**.

---

## 2️⃣ Details Dataset (`details.csv`)

This dataset contains product-level information for each order:

* Order ID
* Product Category
* Sub Category
* Quantity
* Amount
* Profit
* Payment Mode

This dataset helps analyze **product performance, revenue, and profit distribution**.

---

# 🔗 Data Relationship

Both datasets are connected using the **Order ID** field.

```
Orders.csv  ───── Order ID ─────  Details.csv
```

This relationship allows Power BI to combine **order-level and product-level information** for deeper analysis.

---

# 📊 Dashboard Insights

The dashboard includes multiple analytical views:

### Sales by State

Displays revenue distribution across different states to identify top-performing regions.

### Quantity by Category

Shows product demand across categories such as:

* Clothing
* Electronics
* Furniture

### Profit by Month

Tracks monthly profit trends to identify growth patterns.

### Profit by Sub-Category

Provides insights into profitability of product types like:

* Printers
* Phones
* Accessories
* Bookcases
* Sarees

### Payment Mode Analysis

Shows how customers prefer to pay:

* Cash on Delivery (COD)
* UPI
* Debit Card
* Credit Card
* EMI

### Top Customers

Highlights customers contributing the highest sales.

---

# 🛠 Tools & Technologies Used

* **Power BI Desktop**
* **Power Query**
* **Data Modeling**
* **Interactive Data Visualization**

---

# 📂 Project Structure

```
Powerbi-ecom-sales-dashboard
│
├── Mann_Ecommerce_Sales_Dashboard.pbix
├── orders.csv
├── details.csv
├── dashboard_preview.png
└── README.md
```

---

# 🖼 Dashboard Preview

![Dashboard Preview](dashboard_preview.png)

---

# 💡 Key Learnings

This project helped me gain practical experience in:

* Data cleaning and transformation
* Data modeling in Power BI
* Creating interactive dashboards
* Extracting business insights from raw data
* Presenting analytics visually

---

# 🚀 Future Improvements

Potential enhancements include:

* Adding **advanced DAX calculations**
* Implementing **time-series forecasting**
* Connecting the dashboard with **live databases**
* Automating **data refresh pipelines**

---

# 👨‍💻 Author

**Mann Kumar**

Aspiring **Data Analyst | QA Manual & Automation Tester**

GitHub:
https://github.com/Mannkr07

---

⭐ If you found this project useful, feel free to **star the repository**.
