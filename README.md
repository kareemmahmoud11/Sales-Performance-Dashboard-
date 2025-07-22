# Business Performance Analysis Dashboard for Retail Store

# 📊 Sales Performance Dashboard (2015–2017)

Welcome to a comprehensive Power BI dashboard that analyzes sales performance, customer behavior, product trends, returns, and target achievement over the years 2015, 2016, and 2017. This report was developed as a professional Business Intelligence project using real-time data modeling, DAX measures, and effective storytelling techniques.
---

## 🧠 About the Project

This project simulates a real-world BI solution where raw data from multiple sources (sales, returns, customers, products) was cleaned, modeled, and analyzed to provide actionable insights. It covers:

- Revenue and Profit trends
- Product performance
- Customer loyalty
- Return behavior
- Year-over-Year comparisons
- Target vs Actual achievement

---

## 🔧 Tools & Techniques Used

- **Power BI** for data visualization and reporting  
- **Power Query** for data transformation and combining multiple years into one dataset  
- **Star & Snowflake Schema** modeling with proper relationships  
- **DAX** for advanced calculations  
- **Buttons & Page Navigation** for a user-friendly dashboard experience  

---

## 📁 Data Sources

- Sales Data: 2015, 2016, 2017 (appended into one total sales table)
- Calendar table
- Product, Category, Subcategory tables
- Customers table
- Returns table
- Territories table

---

## 🧩 Data Modeling

- Two fact tables: `Sales` and `Returns`
- Lookup tables: `Customers`, `Products`, `Categories`, `Territories`, `Calendar`
- Used **One-to-Many relationships** for accuracy and performance
- Implemented both **Star Schema** and **Snowflake Schema** structures

---

## 📋 Dashboard Pages

### 🔷 1. Landing Page
- Executive summary and navigation to report sections
- Key KPIs and report overview
<img width="1277" height="716" alt="image" src="https://github.com/user-attachments/assets/29344611-92f6-43f1-81a2-a73460025c59" />


### 📊 2. Summary
- 💰 **Total Price**: 24.60 Million  
- 💵 **Total Revenue**: 24.91 Million  
- 📈 **Total Profit**: 10.58 Million  
- 👥 **Total Customers**: 18.02K  
- 📊 **Profit Margin**: 43% of Total Price  
- 🌍 **Top Region**: Australia  
- 🗓️ **Yearly Breakdown**:
  - **2015**: Revenue: 6.4M | Profit: 2.6M  
  - **2016**: Revenue: 9.3M | Profit: 4M  
  - **2017**: Revenue: 9.2M | Profit: 4M
  
<img width="1284" height="729" alt="image" src="https://github.com/user-attachments/assets/1e87c97d-82e1-4f10-983e-27d69ecfe3ff" />

### 📦 3. Products
- 🥇 **Top Selling Category**: Bikes  
- ❌ **Least Selling Category**: Components (0 sales in 3 years)  
- 📊 **YoY Revenue Growth**:
  - 2016: +45.85%
  - 2017: -1.49%
- 📦 **Total Quantity Ordered**: 84K units  
- 📦 **Bulk Orders Quantity (>1)**: 15K  
- 📦 **Total Orders**: 25K

<img width="1285" height="728" alt="image" src="https://github.com/user-attachments/assets/85eb6d00-e3f5-4985-8a98-c879a14edccd" />

### 👥 4. Customers
- 👤 **Total Customers**: 18.02K  
- 🔁 **Repeat Customers**: 15K+  
- 🧠 Insights into loyalty and purchasing patterns

<img width="1294" height="743" alt="image" src="https://github.com/user-attachments/assets/5c52b663-5193-486c-aba3-f57a3ed161d3" />

### 🔁 5. Return Orders
- 🔢 **Total Return Orders**: 1,809  
- 📦 **Total Return Quantity**: 1,828  
- 💸 **Return Revenue**: 765.28K  
- 📉 **Return Orders %**: 7% of total  
- 📉 **Return Revenue %**: 3% of total revenue  
- 🗓️ **Highest Return Year**: 2017

<img width="1295" height="742" alt="image" src="https://github.com/user-attachments/assets/b388682b-b051-4f7f-80b3-c4b774b8c2cf" />

### 🎯 6. Target vs Actual
- 🚀 Company targets:
  - +1.5x Revenue Growth Year-over-Year
  - +1.2x Profit Growth Year-over-Year
- 📈 Performance measured vs these goals annually

<img width="1297" height="722" alt="image" src="https://github.com/user-attachments/assets/5b6bc877-7d52-4942-9147-fde2fe03c0dc" />


---

## 📈 Sample KPIs Displayed

| KPI               | Value         |
|------------------|---------------|
| Total Revenue     | 24.91M        |
| Total Profit      | 10.58M        |
| Total Customers   | 18.02K        |
| Return Orders     | 1,809         |
| Return Rate       | 7%            |
| Profit Margin     | 43%           |
| Top Region        | Australia     |

---

## 🚀 How to Use the Dashboard

1. Open the Power BI file: `Dashboard.pbix`
2. Use the **Landing Page** to navigate to different analysis sections
3. Filter by year, category, or customer segment to explore data
4. Review KPIs and visuals on each page

---





✅ *This dashboard reflects real-world BI practices, including clean data modeling, KPI design, and actionable insights for business growth.*

