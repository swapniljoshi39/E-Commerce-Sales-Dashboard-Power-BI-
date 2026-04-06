# 📊 E-Commerce Sales Dashboard (Power BI)

🚀 This project showcases an interactive **E-Commerce Sales Dashboard** built using Power BI to analyze sales performance, profit trends, and customer behavior.

---

## 📌 Project Overview

The dashboard provides a comprehensive view of:
- Total Sales, Profit, Orders, and Profit %
- Sales distribution across categories
- Monthly sales trends
- Payment mode analysis
- State-wise profit performance
- Category-wise quantity distribution

This project demonstrates skills in **data analysis, data visualization, and business intelligence**.

---

## 📊 Key Metrics

- 💰 **Total Sales:** 438K  
- 📦 **Total Orders:** 1K  
- 📈 **Total Profit:** 37K  
- 📊 **Profit %:** 8.44%  

---

## 🔍 Key Insights

- 📌 Electronics category leads in total sales  
- 👕 Clothing category has the highest quantity sold  
- 💳 Cash on Delivery (COD) is the most used payment method  
- 🗺️ Maharashtra generates the highest profit  
- 📅 Sales trend shows peaks in **January, March, and November**

---

## 🛠 Tools & Technologies Used

- Power BI  
- DAX (Data Analysis Expressions)  
- Data Modeling  
- Data Visualization  

---

## 📂 Dataset Description

The dataset contains the following fields:

- Order ID  
- Order Date  
- Customer Name  
- State  
- Category  
- Sub-Category  
- Payment Mode  
- Quantity  
- Amount (Sales)  
- Profit  

---

## 📈 DAX Measures Used

```DAX
Total Sales = SUM(Orders[Amount])

Total Profit = SUM(Orders[Profit])

Total Orders = DISTINCTCOUNT(Orders[Order ID])

Total Quantity = SUM(Orders[Quantity])

Profit % = DIVIDE([Total Profit], [Total Sales], 0) * 100
