# 🛒 Target: Exploring ecommrece Trends and customer behaviour

## 📌 Project Overview
This project focuses on analyzing **Target’s e-commerce operations in Brazil** using **SQL on Google BigQuery**.  
The goal is to uncover insights related to **order trends, customer distribution, payments, delivery performance, and regional behavior** to support data-driven business decisions.

The analysis is entirely SQL-driven and demonstrates practical data analytics workflows applied to real business questions.

---

## 🗂️ Dataset Description
The dataset represents Target’s Brazilian e-commerce ecosystem and consists of multiple relational tables.

### Tables Used
- **customers** – customer location and unique identifiers  
- **orders** – order lifecycle timestamps  
- **order_items** – product-level details and freight costs  
- **payments** – payment methods, values, and installments  

---

## 🛠️ Tools & Technologies
- **SQL**
- **Google BigQuery**
- **BigQuery Console**
- **GitHub**

---

## 🎯 Business Questions Answered

### 1️⃣ Data Exploration
- What is the time range of the dataset?
- How many orders were placed across cities and states?
- What are the key data types and structures?

### 2️⃣ Order Trends Analysis
- How have orders grown year-over-year?
- What are the monthly ordering patterns?
- At what time of day are most orders placed?

### 3️⃣ Customer & Regional Insights
- How are orders distributed across Brazilian states?
- What is the customer distribution by state?
- Which regions contribute the most orders?

### 4️⃣ Revenue & Logistics Analysis
- How has payment value changed year-over-year?
- What is the total and average order value per state?
- How does freight cost vary across regions?

### 5️⃣ Delivery & Payment Behavior
- How do estimated and actual delivery times compare?
- Which states have the fastest and slowest deliveries?
- What payment methods are most commonly used?
- How do payment installments impact order volume?

---

## 🧠 SQL Concepts Used
- `INNER JOIN`, `LEFT JOIN`
- Aggregate functions: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`
- `GROUP BY`, `ORDER BY`
- Date & time functions: `EXTRACT`, `DATE_DIFF`
- Conditional logic using `CASE WHEN`
- Common Table Expressions (CTEs)

---

## 📊 Key Insights
- Orders show **steady growth over time**, indicating business expansion
- Customer demand and revenue vary significantly by state
- Freight cost and delivery time differ widely across regions
- Certain payment types and installment options dominate customer preference
- Order timing analysis highlights peak hours for potential targeted marketing

---

## 📁 Repository Structure
