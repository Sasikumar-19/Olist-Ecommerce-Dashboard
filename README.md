##  Deep Dive Analysis & Interactive Dashboard  
 
This repository contains the complete workflow for **Task 3**, where I performed a **deep-dive analysis on the Olist Brazilian E-Commerce dataset**, created business KPIs, and developed an **interactive Power BI dashboard** to visualize insights.

The objective of this task was to transform raw transactional data into meaningful insights related to **sales performance, customer behavior, product demand, and delivery efficiency**.

---

## 🔧 1️⃣ Data Loading & Preprocessing (Working Process)

## ✔ Loaded Multiple Datasets
- Imported datasets using **Python and Pandas**
- Performed initial inspection to understand data structure

Datasets used:

- Orders
- Order Items
- Customers
- Payments
- Products
- Sellers
- Reviews

---

## ✔ Data Merging Process

To create a unified dataset, multiple tables were merged using common keys:

- **Orders + Order Items**
- **Orders + Customers**
- **Orders + Payments**
- **Order Items + Products**
- **Order Items + Sellers**
- **Orders + Reviews**

This produced a **Master Dataset** containing order, product, customer, payment, and review information.

---

## ✔ Date & Time Processing

Timestamp columns were converted to datetime format.

Extracted new features:

- Year
- Month
- Day

This enabled **time-based analysis of sales trends**.

---

## ✔ Feature Engineering

A new column was created for revenue calculation.

Revenue = Price + Freight Value

This represents the **total value of each transaction**.

---

# 📊 2️⃣ KPI Creation (Business Metrics)

Key Performance Indicators were defined to measure the performance of the e-commerce platform.

### ⭐ KPIs Created

- **Total Revenue** – Total sales generated
- **Total Orders** – Number of unique orders
- **Total Customers** – Unique customer count
- **Average Order Value (AOV)** – Average spending per order
- **Average Review Score** – Overall customer satisfaction

These KPIs provide a **high-level overview of business performance**.

---

# 🔍 3️⃣ Deep Dive Analysis

Detailed analysis was performed to uncover patterns in sales and customer behavior.

### 🔥 Revenue Trend Analysis
- Studied monthly revenue trends
- Identified periods of higher sales activity

### 🔥 Product Category Performance
- Evaluated revenue contribution by product category
- Identified top-performing categories

### 🔥 Payment Method Analysis
- Examined customer payment preferences
- Identified dominant payment methods

### 🔥 Delivery Performance vs Customer Satisfaction
- Calculated delivery time
- Compared delivery performance with review scores
- Observed impact of logistics on customer satisfaction

---

## 📊 Dashboard Preview
<img width="1301" height="733" alt="image" src="https://github.com/user-attachments/assets/cd69e070-ff9b-4326-9848-6408df255f3e" />


---

# 📊 Key Insights

- Certain product categories generate the majority of revenue
- São Paulo contributes the highest share of sales
- Credit cards are the most commonly used payment method
- Faster delivery improves customer satisfaction
- Sales patterns vary across different months

---

# 🛠 Tools & Technologies Used

- Python
- Pandas
- Power BI
- Jupyter Notebook
 

 
