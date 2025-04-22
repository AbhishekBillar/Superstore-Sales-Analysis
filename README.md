# 📊 Superstore Sales Analysis Dashboard

## 📁 Project Overview

This Power BI dashboard was developed using the **Superstore Sales Data** extracted from a CSV file. The dataset includes sales transactions across various **regions, products, customers, and shipping modes**. After importing the dataset into Power BI, I performed **basic data cleaning** to ensure consistent data types and structure.

---

## 🧮 Key Measures Created

- **Total Sales** – Sum of all sales transactions.
- **Total Orders** – Count of unique order IDs.
- **Average Sales per Order** –  
  `Avg Sales per Order = DIVIDE([Total Sales], [Total Orders], 0)`

---

## 📈 Visualizations & Insights

### 1. Monthly Sales Trend (Line Chart)
- **Fields Used:**  
  X-axis: Order Date (by Month)  
  Y-axis: Total Sales  
- **Purpose:**  
  This chart shows how sales changed each month. It helps us identify months with high or low sales. For example, December had high sales, likely due to holiday shopping.

---

### 2. Sales Performance Over Region (Pie Chart)
- **Fields Used:** Region and Total Sales  
- **Purpose:**  
  It shows how much each region (like West, South) contributed to total sales. We can quickly see which regions are performing better.

---

### 3. Order Distribution by Shipping Mode (Bar Chart)
- **Fields Used:** Ship Mode and Total Orders  
- **Purpose:**  
  This shows which shipping method customers preferred. “Standard Class” had the most orders, showing it is the most used shipping option.

---

### 4. Top 5 Customers by Sales (Table)
- **Fields Used:** Customer Name and Total Sales  
- **Purpose:**  
  It shows the top customers who spent the most. Helps businesses target loyal or high-value customers.

---

### 5. Top 5 Best-Selling Products (Table)
- **Fields Used:** Product Name and Total Sales  
- **Purpose:**  
  It helps identify the best-performing products. Useful for decision-making in marketing and sales strategies.

---

## 🎓 What I Learned

- Choosing the right visuals for each type of data:  
  Line charts for trends, pie charts for proportions, and tables for top-n analysis.
- Creating custom DAX measures to extract meaningful business insights.
- Using visual-level filters to display focused data like top customers or products.
- Designing clean and interactive dashboards using slicers for year, category, sub_category, etc.

---

## 📷 Dashboard Preview

![dashboard_preview](https://github.com/user-attachments/assets/2df6cb9c-5c28-46d1-8f8e-42a3f7ba98cb)


---

> ✅ This project helped me improve my Power BI skills in data cleaning, visual design, and business storytelling.
