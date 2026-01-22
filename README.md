
# 📊 Retail & Marketing Analytics  
### End-to-End Data Analyst Project (Python | Power BI)

---

## 🔍 Project Overview

This project demonstrates an **end-to-end Retail & Marketing Analytics workflow**, covering data cleaning, exploratory analysis, customer analytics, and dashboard creation.

The objective is to transform raw retail transaction data into **actionable business insights** using **Python for analysis** and **Power BI for visualization** **.

---

## 🎯 Business Objectives

- Track overall business performance using key KPIs
- Understand customer purchasing behavior
- Identify high-value and at-risk customers
- Analyze customer lifetime value (CLV)
- Evaluate product and category performance
- Build an executive-ready interactive dashboard

---

## 🗂 Dataset Information

- **Source:** Kaggle – Retail Sales Dataset  
- **Type:** Transactional retail data  
- **Records:** ~10,000 transactions  
- **Time Period:** Jan 2022 – Feb 2023  

### Key Fields
- Customer ID  
- Order Date  
- Revenue & Profit  
- Product & Category  
- Quantity Purchased  

---

## 🛠 Tools & Technologies

- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **Power BI:** Dashboard design and reporting  
- **Jupyter Notebook:** Analysis and EDA  

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Cleaning (Python)
- Loaded raw CSV data into Python
- Removed duplicates and invalid records
- Handled missing values
- Converted data types (dates, numeric fields)
- Created derived metrics

---

### 2️⃣ Exploratory Data Analysis (EDA)

Performed multiple types of analysis:
- **Univariate Analysis:**  
  Revenue, orders, quantity, CLV distributions
- **Bivariate Analysis:**  
  Customer frequency vs revenue, category vs revenue
- **Time-Series Analysis:**  
  Monthly revenue and order trends
- **Product & Category Analysis:**  
  Revenue contribution by category and product

---

### 3️⃣ Customer Analytics

#### RFM Segmentation
Customers were segmented using:
- **Recency:** Last purchase date
- **Frequency:** Number of purchases
- **Monetary:** Total spend

Segments identified:
- **High Value Customers**
- **Medium Value Customers**
- **Low value Customers**

#### Customer Lifetime Value (CLV)
- Calculated CLV to estimate long-term customer profitability
- Observed a right-skewed CLV distribution 

---

### 4️⃣ Power BI Dashboard

A **4-page interactive Power BI dashboard** was created:

![Retail Analysis Dashboard](dashboard/Executive_Summary.png)
![Retail Analysis Dashboard](dashboard/RFM_Analytics.png)
![Retail Analysis Dashboard](dashboard/Product_Performance.png)
![Retail Analysis Dashboard](dashboard/CLV_Distribution.png)

---

#### 📌 Page 1: Executive Overview
- KPIs: Revenue, Orders, Customers, AOV, CLV
- Monthly revenue trend
- Revenue by category
- Sales by Product and Sub-Product category
- Region slicer

#### 📌 Page 2: Customer Segmentation (RFM)
- Customer count by segment
- Revenue contribution by segment
- Average RFM for each segment

#### 📌 Page 3: Customer Value (CLV)
- Average CLV for each segment
- Top customers by CLV

#### 📌 Page 4: Product Performance
- Top 10 products by revenue
- Month-wise Quantity sold for each product category
- Top 10 most sold Product sub category
- Profit Margin for each Product sub category
- Region slicer

---

## 📈 Key Business Metrics

- **Total Revenue:** $1.08M  
- **Total Profit:** $198K  
- **Profit Margin:** 18.38%  
- **Average Order Value:** $107.87  
- **Total Customers:** 1,986    
- **Average CLV:** $1.03K  

---

## 💡 Key Insights

- Revenue is highly concentrated among medium value customers
- Low value Customers have the highest average CLV
- A large number of customers are low value and needs measures for re-engagement
- Electronics category brings maximum of revenue
- Chairs and Phones are the top most products to be sold

---

## 📌 Business Recommendations

- Prioritize retention strategies for high value customers
- Run win-back campaigns for at-risk customers
- Optimize inventory and promotions for top categories
- Track KPIs regularly using dashboards

---

## 📁 Repository Structure

├── notebooks/
│ ├── 01_Data_Loading_&_Cleaning.ipynb
│ ├── 02_exploratory_data_analysis.ipynb
│ ├── 03_customer_segmentation_rfm.ipynb
│ └── 04_kpi_calculation.ipynb
├── dashboard/
│ └── Retail Analysis.pbix
├── data/
│ └── raw_data.csv
│ └── processed_data.csv
├── reports/
│ └── kpi_summary.csv
│ └── monthly_kpis.csv
│ └── rfm_segment_summary.csv
│ └── Final_Report_Retail_Analytics.pdf
├── figures/
├── README.md




---

## 📌 Project Outcome

This project showcases:
- End-to-end data analysis workflow
- Strong fundamentals in Python and Power BI
- Business-focused analytics and storytelling
- Dashboard-driven decision-making

---

## 👤 Author

**[Deepanshu Jain]**  
Data Analyst  
Python | SQL | Power BI  

---
