
# Retail & Marketing Analytics  
### End-to-End Data Analyst Project (Python | Power BI)

---

## Project Overview

This project demonstrates an **end-to-end Retail & Marketing Analytics workflow**, covering data cleaning, exploratory analysis, customer analytics, and dashboard creation.

The objective is to transform raw retail transaction data into **actionable business insights** using **Python for analysis** and **Power BI for visualization**.

---

##  Business Objectives

- Identify high-value customers using segmentation
- Analyze sales trends and performance
- Evaluate product-level profitability
- Build dashboards to support data-driven decision-making

---

##  Dataset Information

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

## Tools & Technologies

- **Python:** Pandas, Matplotlib, Seaborn
- **Power BI:** Dashboard design and reporting  
- **Jupyter Notebook:** Analysis and EDA  

---

## Project Workflow

### 1️ Data Loading & Cleaning (Python)
- Loaded raw CSV data into Python
- Removed duplicates and handled outliers
- Handled missing values
- Converted data types (dates, numeric fields)
- Created derived metrics

---

### 2️ Exploratory Data Analysis (EDA)

Performed multiple types of analysis:
- **Univariate Analysis:**  
  Revenue, orders, quantity
- **Bivariate Analysis:**  
  Customer frequency vs revenue, category vs revenue
- **Time-Series Analysis:**  
  Monthly revenue and order trends
- **Product & Category Analysis:**  
  Revenue contribution by category and product

---

### 3️ Customer Analytics

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

### 4️ Power BI Dashboard

A **3-page interactive Power BI dashboard** was created:

![Retail Analysis Dashboard](Dashboard/customer analytics.png)
![Retail Analysis Dashboard](Dashboard/RFM_Analytics.png)
![Retail Analysis Dashboard](Dashboard/ProductPerformance.png)

---

#### Page 1: Executive Overview
- KPIs: Revenue,Profit, Orders, Customers, AOV, CLV
- Monthly revenue trend
- Revenue by category
- Sales by Product 
- Region, category, month slicers

#### Page 2: Customer Segmentation (RFM and CLV)
- Customer count by Lifetime Value
- Revenue contribution by RFM segment
- Average RFM and CLV for each segment
- Top 10 High value customers

#### Page 3: Product Performance
- Top 10 products by revenue
- Month-wise Quantity sold for each product category
- Top 10 most sold Product sub category
- Profit Margin for each Product sub category
- Region and month slicers

---

##  Key Business Metrics

- **Total Revenue:** $1.08M  
- **Total Profit:** $198K  
- **Profit Margin:** 18.38%  
- **Average Order Value:** $107.87  
- **Total Customers:** 1,986    
- **Average CLV:** $1.03K  

---

## Key Insights

- Revenue is stable but shows a recent decline - requires investigation
- Medium-value customers dominate - strong upselling potential
- Electronics category drives maximum revenue
- A small group of customers contributes disproportionately to CLV
- Product profitability varies - need margin-focused strategies

---

## Business Recommendations

- Target medium-value customers with loyalty programs to increase CLV
- Retain high-value customers through personalized offers
- Investigate revenue drop post-Jan 2023
- Optimize pricing for low-margin product categories

---

##  Repository Structure
```

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

```


---

## Project Outcome

This project showcases:
- End-to-end data analysis workflow
- Strong fundamentals in Python and Power BI
- Business-focused analytics and storytelling
- Dashboard-driven decision-making

---

## Author

**[Deepanshu Jain]**  
Data Analyst  
Python | SQL | Power BI  

---
