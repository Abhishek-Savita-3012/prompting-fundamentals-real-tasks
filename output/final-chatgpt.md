# 📊 Retail Sales & Inventory Analytics

An end-to-end **Data Analytics** project that analyzes retail sales, customer behavior, inventory performance, and future sales trends using **SQL, Python, Machine Learning, and Power BI**. This project transforms raw retail data into actionable business insights, enabling data-driven decision-making for retail businesses.

---

# Project Overview

Retail businesses generate vast amounts of transactional and inventory data every day. Extracting meaningful insights from this data is essential for improving profitability, optimizing inventory, understanding customer behavior, and forecasting future sales.

This project demonstrates a complete analytics workflow—from data extraction and cleaning to business analysis, predictive modeling, and interactive dashboard development. It combines SQL for business analysis, Python for data processing and machine learning, and Power BI for executive reporting.

The project is designed to showcase practical skills required for **Data Analyst**, **Business Intelligence**, and **Data Analytics** roles.

---

# Key Features

- 📈 SQL-based business analysis
- 🧹 Exploratory Data Analysis (EDA) using Python
- 👥 Customer Segmentation using RFM Analysis
- 📦 ABC Inventory Analysis
- 🤖 Sales Forecasting using Linear Regression
- 💰 Revenue and Profit Analysis
- 🛍️ Product Profitability Analysis
- 🛒 Customer Purchasing Behavior Analysis
- 📊 Interactive Power BI Dashboard
- 📉 Sales Trend Analysis
- 📍 Geographic Revenue Analysis
- 📅 Monthly and Yearly Business Performance Reporting

---

# Technologies Used

| Category | Technologies |
|----------|--------------|
| Database | SQL, MySQL |
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Business Intelligence | Power BI |
| Data Modeling | DAX |
| Data Source | Excel |

---

# Project Architecture

```
                 Retail Dataset (Excel)
                         │
                         ▼
                 Data Cleaning (Python)
                         │
                         ▼
           Exploratory Data Analysis (EDA)
                         │
                         ▼
              SQL Business Analysis (MySQL)
                         │
         ┌───────────────┼────────────────┐
         ▼               ▼                ▼
 Customer Analysis   Inventory Analysis  Revenue Analysis
         │               │                │
         └───────────────┼────────────────┘
                         ▼
            Machine Learning Forecasting
              (Linear Regression Model)
                         │
                         ▼
              Power BI Interactive Dashboard
                         │
                         ▼
               Business Insights & Reporting
```

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/retail-sales-inventory-analytics.git
```

## Navigate to the Project Directory

```bash
cd retail-sales-inventory-analytics
```

## Install Required Python Packages

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Open the Power BI Dashboard

Open the `.pbix` file using **Microsoft Power BI Desktop**.

---

# Usage

### 1. SQL Analysis

- Import the dataset into MySQL.
- Execute SQL scripts to perform:
  - Revenue Analysis
  - Profit Analysis
  - Customer Analysis
  - Product Analysis
  - Sales Trend Analysis

---

### 2. Python Analysis

Run the Jupyter Notebook to perform:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Customer Segmentation
- Inventory Analysis
- Sales Forecasting

Example:

```bash
jupyter notebook
```

---

### 3. Power BI Dashboard

Open the Power BI report to explore:

- Executive Overview
- Customer Analytics
- Inventory Analytics
- Sales Forecast & Trends

Use interactive filters and slicers to analyze business performance across products, customers, regions, and time periods.

---

# Dashboard Screenshots

## Executive Overview

![Executive Overview](images/dashboard_screenshots/executive_overview.png)

Provides a high-level summary of key business KPIs, revenue trends, profit metrics, and geographic sales distribution.

---

## Customer Analytics

![Customer Analytics](images/dashboard_screenshots/customer_analytics.png)

Includes RFM segmentation, customer purchasing behavior, repeat customer analysis, and customer value insights.

---

## Inventory Analytics

![Inventory Analytics](images/dashboard_screenshots/inventory_analytics.png)

Visualizes ABC inventory classification, inventory value distribution, product stock analysis, and inventory optimization insights.

---

## Sales Forecast & Trends

![Sales Forecast & Trends](images/dashboard_screenshots/sales_forecast.png)

Displays historical sales trends, monthly performance, and future sales forecasting using a Linear Regression model.

---

# Business Insights

### Revenue Analysis

- Electronics generated the highest overall revenue.
- Revenue varied significantly across different states and months.
- Seasonal trends influenced sales performance.

### Customer Segmentation

RFM Analysis identified five major customer segments:

- 🏆 Champions
- 🤝 Loyal Customers
- 💎 Big Spenders
- 👤 Regular Customers
- ⚠️ At-Risk Customers

These segments help businesses develop targeted marketing strategies and improve customer retention.

### Inventory Analysis

ABC Analysis classified products into:

- **Class A** – High-value inventory requiring close monitoring.
- **Class B** – Moderate-value inventory with balanced management.
- **Class C** – Low-value inventory requiring minimal control.

This classification supports efficient inventory planning and resource allocation.

### Sales Forecasting

A Linear Regression model was developed to forecast future sales trends, providing a foundational predictive analytics approach for demand planning.

### Product Profitability

- High-revenue products were identified.
- Profitability analysis highlighted products contributing the most to overall business performance.
- Insights support pricing, inventory, and product portfolio decisions.

### Customer Purchasing Behavior

Customer purchase patterns were analyzed to understand:

- Buying frequency
- Purchase value
- Customer lifetime contribution
- Revenue contribution by customer segment

These insights enable data-driven marketing and customer engagement strategies.

---

# Future Improvements

- Implement advanced forecasting models such as ARIMA, Prophet, or XGBoost.
- Develop automated ETL pipelines for continuous data updates.
- Integrate real-time data sources.
- Add demand forecasting at product and regional levels.
- Enhance dashboard interactivity with advanced drill-through reports.
- Build customer churn prediction models.
- Deploy the analytics solution as a cloud-based reporting platform.
- Incorporate advanced business KPIs and anomaly detection.

---

# Author

**Abhishek**

**Aspiring Data Analyst | Business Intelligence Enthusiast**

### Skills

- SQL
- MySQL
- Python
- Pandas
- NumPy
- Power BI
- DAX
- Machine Learning
- Data Visualization
- Business Analytics

If you found this project useful, consider giving it a ⭐ on GitHub.
