# 📊 Retail Sales & Inventory Analytics

> End-to-end Retail Sales & Inventory Analytics project using **SQL, Python, Power BI, and Excel** to analyze sales performance, customer behavior, inventory efficiency, and forecast future sales.

![GitHub last commit](https://img.shields.io/github/last-commit/your-username/retail-sales-inventory-analytics)
![GitHub repo size](https://img.shields.io/github/repo-size/your-username/retail-sales-inventory-analytics)
![GitHub stars](https://img.shields.io/github/stars/your-username/retail-sales-inventory-analytics?style=social)

---

# 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Project Architecture](#-project-architecture)
- [Technology Stack](#-technology-stack)
- [Dataset Information](#-dataset-information)
- [Project Workflow](#-project-workflow)
- [Key Features](#-key-features)
- [Dashboard Pages](#-dashboard-pages)
- [Business Insights](#-business-insights)
- [Repository Structure](#-repository-structure)
- [How to Run the Project](#-how-to-run-the-project)
- [Future Improvements](#-future-improvements)
- [Skills Demonstrated](#-skills-demonstrated)
- [Author](#-author)

---

# 📖 Project Overview

Retail businesses generate massive amounts of sales and inventory data every day. However, raw transactional data alone cannot support informed business decisions.

This project transforms retail data into actionable business insights using SQL, Python, and Power BI. It covers the complete analytics workflow—from data cleaning and business analysis to customer segmentation, inventory optimization, sales forecasting, and executive dashboard reporting.

The project demonstrates practical Business Intelligence and Data Analytics skills applicable to real-world retail environments.

---

# 💼 Business Problem

Retail companies often struggle with:

- Identifying top-performing products
- Understanding customer purchasing behavior
- Managing excess and low inventory
- Predicting future sales
- Tracking KPIs efficiently
- Making data-driven business decisions

Without analytics, organizations may experience:

- Overstocking
- Stockouts
- Revenue loss
- Low customer retention
- Poor inventory planning

This project addresses these challenges through interactive analytics and visualization.

---

# 🎯 Project Objectives

The primary objectives of this project are:

- Analyze retail sales performance
- Measure business KPIs
- Identify high-value customers
- Perform RFM Customer Segmentation
- Analyze inventory using ABC Analysis
- Forecast future sales
- Discover profitable products
- Build interactive Power BI dashboards
- Generate business insights for decision-making

---

# 🏗 Project Architecture

```
                Retail Dataset
                       │
                       ▼
              SQL Data Analysis
                       │
                       ▼
        Python Data Cleaning & EDA
                       │
                       ▼
      Feature Engineering & Analytics
                       │
        ┌──────────────┴──────────────┐
        ▼                             ▼
 Customer Segmentation        Inventory Analysis
 (RFM Model)                  (ABC Analysis)
        │                             │
        └──────────────┬──────────────┘
                       ▼
             Sales Forecasting
                       │
                       ▼
          Power BI Interactive Dashboard
```

---

# 🛠 Technology Stack

| Category | Tools |
|----------|-------|
| Programming | Python |
| Database | MySQL |
| Query Language | SQL |
| Data Processing | Pandas, NumPy |
| Visualization | Power BI |
| Dashboard Language | DAX |
| ETL | Power Query |
| Machine Learning | Scikit-learn |
| Charts | Matplotlib |
| Spreadsheet | Microsoft Excel |
| Version Control | Git & GitHub |

---

# 📂 Dataset Information

The project uses a retail sales dataset containing:

### Customers

- Customer ID
- Customer Name
- Gender
- Age
- City
- State
- Join Date

### Products

- Product ID
- Product Name
- Category
- Sub Category
- Cost Price
- Selling Price

### Sales

- Order ID
- Order Date
- Customer ID
- Product ID
- Quantity
- Discount

### Inventory

- Product Stock
- Warehouse
- Inventory Value
- Stock Level

---

# 🔄 Project Workflow

```
Data Collection

        ↓

Data Cleaning (Python)

        ↓

Exploratory Data Analysis

        ↓

SQL Business Analysis

        ↓

Customer Segmentation

        ↓

ABC Inventory Analysis

        ↓

Sales Forecasting

        ↓

Power BI Dashboard

        ↓

Business Insights
```

---

# 🚀 Key Features

## SQL Analytics

- Revenue Analysis
- Sales Trend Analysis
- Product Performance
- Customer Analysis
- Profit Analysis
- Monthly KPIs

---

## Python Analytics

- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization

---

## Customer Analytics

- RFM Segmentation
- Customer Frequency
- Monetary Value Analysis
- Customer Retention Analysis
- High-Value Customer Identification

Customer Segments:

- 🏆 Champions
- 💚 Loyal Customers
- 💙 Big Spenders
- 🟢 Regular Customers
- ❤️ At Risk Customers

---

## Inventory Analytics

ABC Inventory Analysis

- Class A Products
- Class B Products
- Class C Products

Inventory KPIs

- Inventory Value
- Stock Quantity
- Warehouse Performance
- Inventory Distribution

---

## Sales Forecasting

Implemented using:

- Linear Regression
- Historical Sales Trends
- Monthly Forecast Analysis

---

## Interactive Power BI Dashboard

Features include:

- Executive KPI Dashboard
- Dynamic Filters
- Drill-through Reports
- Interactive Charts
- Maps
- Trend Analysis
- Forecast Visualization

---

# 📈 Dashboard Pages

## Executive Overview

KPIs

- Total Revenue
- Total Profit
- Orders
- Customers
- Average Order Value
- Inventory Value

Visuals

- Revenue Trend
- Category Performance
- Revenue by State
- Monthly Sales
- KPI Cards

---

## Customer Analytics

Includes:

- RFM Segmentation
- Customer Distribution
- Customer Lifetime Value
- Frequency Analysis
- Monetary Analysis

---

## Inventory Analytics

Includes:

- ABC Classification
- Inventory Value
- Warehouse Analysis
- Product Distribution
- Inventory Health

---

## Sales Forecast & Trends

Includes:

- Monthly Revenue
- Sales Trend
- Forecast Line
- Seasonal Analysis
- Future Sales Prediction

---

# 💡 Business Insights

The analysis revealed several important business insights:

### 📌 Electronics Generate the Highest Revenue

Electronics contribute the largest share of total sales, making them the primary revenue driver.

---

### 📌 Customer Revenue is Highly Concentrated

A relatively small group of customers contributes a significant portion of total revenue, highlighting the importance of retaining high-value customers.

---

### 📌 High Revenue Does Not Always Mean High Profit

Some products generate strong sales but deliver lower profitability due to higher costs or discounts.

---

### 📌 Revenue Varies Across Geographic Regions

Sales performance differs significantly between states, indicating opportunities for targeted regional marketing and inventory allocation.

---

### 📌 Inventory Value is Concentrated in High-Priority Products

ABC Analysis shows that a small percentage of products account for the majority of inventory value, requiring close monitoring and optimized stock management.

---

### 📌 Large Orders Create Sales Outliers

A limited number of high-volume transactions contribute disproportionately to revenue, impacting overall sales distribution.

---

### 📌 Monthly Revenue Shows Seasonal Fluctuations

Sales exhibit recurring monthly variations, reinforcing the need for demand forecasting and inventory planning.

---

# 📁 Repository Structure

```
Retail-Sales-Inventory-Analytics/

│
├── data/
│   ├── raw/
│   ├── processed/
│
├── sql/
│   ├── database.sql
│   ├── analysis.sql
│
├── notebooks/
│   ├── eda.ipynb
│
├── python/
│   ├── data_cleaning.py
│   ├── forecasting.py
│
├── powerbi/
│   ├── Retail Dashboard.pbix
│
├── dashboard_screenshots/
│   ├── executive_overview.png
│   ├── customer_analytics.png
│   ├── inventory_analytics.png
│   ├── sales_forecast.png
│
├── reports/
│
├── README.md
│
└── requirements.txt
```

---

# ▶️ How to Run the Project

## Clone Repository

```bash
git clone https://github.com/your-username/Retail-Sales-Inventory-Analytics.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Import SQL Database

Run the SQL scripts using MySQL Workbench.

---

## Execute Python Analysis

```bash
python data_cleaning.py
```

---

## Open Power BI Dashboard

Open:

```
Retail Dashboard.pbix
```

using Microsoft Power BI Desktop.

---

# 🔮 Future Improvements

Planned enhancements include:

- ARIMA & Prophet Forecasting
- Customer Churn Prediction
- Product Recommendation System
- Automated ETL Pipeline
- Cloud Deployment
- Real-Time Dashboard
- Predictive Inventory Optimization

---

# 🎯 Skills Demonstrated

- SQL Querying
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Data Visualization
- Power BI Dashboard Development
- DAX
- Power Query
- Customer Segmentation
- Inventory Analytics
- Sales Forecasting
- Business Intelligence
- Business Analytics
- KPI Reporting
- Data Storytelling

---

# 👨‍💻 Author

**Abhishek**

B.Tech Computer Science Engineering

Aspiring **Data Analyst | Business Intelligence Analyst**

### Connect with Me

- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/your-profile

---

## ⭐ If you found this project useful, consider giving it a Star!

This repository showcases an end-to-end Retail Sales & Inventory Analytics solution and demonstrates practical skills in SQL, Python, Power BI, and Business Intelligence.
