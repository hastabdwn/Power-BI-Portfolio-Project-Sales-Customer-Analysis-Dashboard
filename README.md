# 🧾 Power BI Portfolio Project — Sales & Customer Analysis Dashboard

A professional **Power BI Data Analyst portfolio project** consisting of two dashboard pages:
1. **Sales Analysis Dashboard**
2. **Customer Analysis Dashboard**

This project demonstrates my ability to perform **data cleaning, transformation, and visualization** using Power BI, focusing on **sales performance** and **customer insights**.

---

## 📊 1️⃣ Sales Analysis Dashboard

### 🎯 Objective
To analyze company sales performance, profitability, and category-wise contribution across regions.

### 🧠 Key Business Questions
- What is the total revenue and profit generated?
- Which country contributes the most to sales?
- How do monthly sales trends perform over time?
- Which product categories drive the most revenue?

---

### 💡 KPI Cards
| Metric | Description |
|---------|-------------|
| **Total Revenue** | Total income generated from sales transactions |
| **Total Profit** | Overall profit after subtracting costs |
| **Profit Margin %** | Profitability ratio = `(Profit / Revenue) * 100` |
| **Total Quantity Sold** | Number of products sold across all categories |

---

### 📈 Visualizations

| Visualization | Description |
|----------------|--------------|
| **Bar Chart — Sales by Country** | Compare total revenue by country or region |
| **Line Chart — Monthly Sales Trend** | Track revenue and profit trends over time |
| **Clustered Bar Chart — Sales by Category** | Identify top-performing product categories |

---

### ⚙️ DAX Measures Used
```DAX
Total Revenue = SUM(vw_sales[Revenue])

Total Profit = SUM(vw_sales[Profit])

Profit Margin % =
DIVIDE(SUM(vw_sales[Profit]), SUM(vw_sales[Revenue])) * 100

Total Quantity = SUM(vw_sales[Quantity])

```

---

### 🧩 Insights
- The **top 3 countries** contribute over 70% of total revenue.  
- **Profit margin** stabilizes around 25–30% across months.  
- **Electronics** and **Accessories** are the best-performing categories.  
- Sales trend shows consistent growth in Q3 and Q4, driven by promotional events.  

---

### 🗂️ Dataset
This project uses the public dataset available on Kaggle:  
📦 **[Sales Data for Economic Data Analysis — Kaggle](https://www.kaggle.com/datasets/abhishekrp1517/sales-data-for-economic-data-analysis)**  

The dataset contains transaction-level sales data with fields such as:  
`Order ID`, `Customer ID`, `Product`, `Category`, `Country`, `Order Date`, `Quantity`, `Revenue`, and `Profit`.

---

### 🛠️ Tools & Tech Stack
- **Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **Power Query**  
- **Excel / PostgreSQL for preprocessing**

---


