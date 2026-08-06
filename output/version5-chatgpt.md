# 🛍️ Retail Sales & Inventory Analytics

A comprehensive end-to-end **Retail Sales & Inventory Analytics** project that combines **SQL, Python, Power BI, Excel, and Machine Learning** to transform raw retail data into actionable business insights.

The project demonstrates the complete analytics workflow—from data extraction and cleaning to customer segmentation, inventory optimization, sales forecasting, and interactive business intelligence dashboards.

Designed as a portfolio project for **Data Analyst** and **Business Intelligence** roles, it showcases real-world analytical skills, business storytelling, and dashboard development.

---

# Project Overview

Retail businesses generate large volumes of sales and inventory data every day. Making effective decisions requires transforming this raw data into meaningful insights.

This project analyzes retail operations to answer important business questions such as:

- Which products generate the highest revenue?
- Which customers are the most valuable?
- Which inventory items require replenishment?
- What sales trends can be observed over time?
- How can future sales be estimated?
- Which business metrics should executives monitor regularly?

The project follows a complete analytics lifecycle:

Raw Data → SQL Analysis → Python EDA → Customer Segmentation → Inventory Analysis → Sales Forecasting → Interactive Power BI Dashboard

---

# Key Features

## 📊 SQL Business Analysis

- Database design and normalization
- Business KPI calculations
- Revenue analysis
- Profit analysis
- Customer purchase analysis
- Product performance analysis
- Monthly sales trends
- Category-wise performance
- Top-selling products
- Sales by region

---

## 🐍 Python Data Analysis

- Data cleaning
- Missing value handling
- Duplicate removal
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Distribution analysis
- Outlier detection
- Feature engineering

---

## 👥 Customer Analytics

- RFM Customer Segmentation
- Customer Lifetime Value indicators
- Repeat customer analysis
- Customer purchase behavior
- Segment-wise revenue contribution

Customer Segments include:

- 🏆 Champions
- 💚 Loyal Customers
- 💙 Big Spenders
- 🟢 Regular Customers
- ❤️ At Risk Customers

---

## 📦 Inventory Analytics

- ABC Inventory Analysis
- Inventory Value Analysis
- Category-wise inventory distribution
- Product contribution analysis
- Inventory optimization insights

---

## 📈 Sales Forecasting

- Monthly sales forecasting
- Linear Regression model
- Historical trend analysis
- Future revenue prediction
- Forecast visualization

---

## 📊 Interactive Power BI Dashboard

The dashboard contains four fully interactive report pages:

### Executive Overview

- Revenue KPI
- Profit KPI
- Orders KPI
- Customers KPI
- Monthly Revenue Trend
- Sales by Category
- Revenue by State
- Revenue by City
- Dynamic Filters

---

### Customer Analytics

- Customer Segments
- RFM Distribution
- Revenue by Segment
- Average Order Value
- Purchase Frequency
- Customer Demographics

---

### Inventory Analytics

- ABC Classification
- Inventory Value Distribution
- Category Performance
- Stock Optimization Insights

---

### Sales Forecast & Trends

- Monthly Sales Trend
- Forecast Chart
- Forecast Table
- Seasonal Trend Analysis
- Revenue Growth Analysis

---

# Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Database | MySQL |
| Query Language | SQL |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Dashboard | Power BI |
| Data Modeling | Power Query, DAX |
| Spreadsheet | Microsoft Excel |
| Version Control | Git & GitHub |

---

# Project Architecture

```text
Retail Sales Dataset
        │
        ▼
MySQL Database
        │
        ▼
SQL Business Analysis
        │
        ▼
Python Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Customer Segmentation (RFM)
        │
        ▼
ABC Inventory Analysis
        │
        ▼
Sales Forecasting
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights
```

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/retail-sales-inventory-analytics.git
```

---

## Navigate to the Project

```bash
cd retail-sales-inventory-analytics
```

---

## Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment:

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Open the Project

- Run SQL scripts in MySQL Workbench.
- Execute the Jupyter notebooks for analysis.
- Open the Power BI (`.pbix`) file to explore the dashboards.

---

# Usage

1. Import the retail dataset into MySQL.
2. Execute the SQL scripts to perform business analysis.
3. Run the Python notebooks for data cleaning and exploratory analysis.
4. Perform RFM customer segmentation.
5. Execute the ABC inventory analysis.
6. Train the sales forecasting model.
7. Open the Power BI dashboard to interact with business reports.
8. Explore insights using filters, slicers, and drill-through functionality.

---

# Dashboard Screenshots

> Replace the image paths below with your actual screenshots.

## Executive Overview

```markdown
![Executive Overview](images/dashboard_screenshots/executive_overview.png)
```

---

## Customer Analytics

```markdown
![Customer Analytics](images/dashboard_screenshots/customer_analytics.png)
```

---

## Inventory Analytics

```markdown
![Inventory Analytics](images/dashboard_screenshots/inventory_analytics.png)
```

---

## Sales Forecast & Trends

```markdown
![Sales Forecast](images/dashboard_screenshots/sales_forecast.png)
```

---

# Business Insights

## 📈 Sales Performance

- Electronics generated the highest overall revenue across all product categories.
- Monthly revenue exhibited noticeable fluctuations, highlighting seasonal purchasing behavior.
- A small subset of products contributed disproportionately to total sales, indicating opportunities for focused inventory management.

---

## 👥 Customer Insights

- A limited group of customers accounted for a significant share of total revenue.
- RFM analysis identified distinct customer segments, enabling targeted marketing and retention strategies.
- Loyal and Champion customers consistently delivered higher revenue and purchase frequency.

---

## 📦 Inventory Insights

- ABC analysis revealed that a relatively small number of products represented the majority of total inventory value.
- Category A items require close monitoring due to their high business impact.
- Inventory value was concentrated in selected warehouses, suggesting opportunities for stock optimization and redistribution.

---

## 💰 Profitability Insights

- Several high-revenue products delivered comparatively lower profit margins, indicating potential pricing or cost optimization opportunities.
- Product profitability varied significantly across categories, emphasizing the need for category-specific strategies.

---

## 📊 Forecasting Insights

- Historical sales trends were used to build a Linear Regression forecasting model.
- The baseline forecasting model demonstrates the complete machine learning workflow while highlighting opportunities for more advanced time-series approaches.

---

# Future Improvements

- Implement Prophet-based time series forecasting.
- Integrate ARIMA and SARIMA forecasting models.
- Develop automated ETL pipelines for scheduled data refresh.
- Connect dashboards to live cloud databases.
- Add anomaly detection for sales and inventory.
- Build a recommendation engine for product optimization.
- Deploy dashboards using Power BI Service.
- Integrate real-time inventory monitoring.
- Expand customer analytics with churn prediction.
- Create executive KPI alert notifications.

---

# Author

**Abhishek**

Aspiring **Data Analyst** | **Business Intelligence Analyst** | **SQL Developer**

### Skills

- SQL
- Python
- Power BI
- Excel
- MySQL
- Pandas
- NumPy
- Scikit-learn
- Data Visualization
- Business Intelligence

If you found this project helpful, consider giving it a ⭐ on GitHub.
