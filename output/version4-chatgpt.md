# 📊 Retail Sales & Inventory Analytics

A comprehensive end-to-end **Retail Sales & Inventory Analytics** project that combines **SQL, Python, Power BI, and Excel** to analyze retail business performance, customer behavior, inventory management, and sales forecasting. The project transforms raw retail data into actionable business insights through data cleaning, exploratory analysis, machine learning, and interactive dashboards.

---

# Project Overview

Retail businesses generate large volumes of sales and inventory data every day. Without proper analysis, it becomes difficult to identify high-performing products, understand customer purchasing behavior, optimize inventory levels, and forecast future sales.

This project demonstrates a complete analytics workflow by:

- Extracting meaningful business insights using SQL
- Performing Exploratory Data Analysis (EDA) with Python
- Segmenting customers using RFM Analysis
- Classifying inventory using ABC Analysis
- Building sales forecasting models
- Designing interactive Power BI dashboards for decision-making

This project is designed to showcase practical Business Intelligence and Data Analytics skills for **Data Analyst** and **Business Intelligence** roles.

---

# Key Features

- 📈 Sales Performance Analysis
- 🛍️ Product Revenue & Profitability Analysis
- 👥 Customer Segmentation using RFM Analysis
- 📦 ABC Inventory Classification
- 📉 Monthly & Yearly Sales Trend Analysis
- 💰 Revenue & Profit KPIs
- 🏙️ Region & City-wise Performance Analysis
- 📊 Interactive Power BI Dashboard
- 🐍 Python-based Data Cleaning & EDA
- 🔍 SQL Business Queries & KPI Analysis
- 🤖 Sales Forecasting using Linear Regression
- 📉 Inventory Optimization Insights

---

# Technologies Used

| Category | Technologies |
|----------|--------------|
| Database | MySQL |
| Query Language | SQL |
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Dashboard | Power BI |
| Data Transformation | Power Query |
| BI Calculations | DAX |
| Spreadsheet | Microsoft Excel |
| Version Control | Git & GitHub |

---

# Project Architecture

```text
                   Retail Dataset
                          │
                          ▼
                 Data Cleaning (Python)
                          │
                          ▼
              Exploratory Data Analysis
                          │
          ┌───────────────┴───────────────┐
          ▼                               ▼
     SQL Business Analysis          Python Analytics
          │                               │
          ├───────────────┬───────────────┤
                          ▼
                 Feature Engineering
                          │
          ┌───────────────┼───────────────┐
          ▼               ▼               ▼
     RFM Analysis    ABC Analysis   Sales Forecasting
          │               │               │
          └───────────────┼───────────────┘
                          ▼
                 Power BI Dashboard
                          │
                          ▼
                Business Decision Making
```

---

# Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/retail-sales-inventory-analytics.git
```

### 2. Navigate to the Project

```bash
cd retail-sales-inventory-analytics
```

### 3. Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Import SQL Database

- Open MySQL Workbench.
- Create the database.
- Import the SQL scripts from the `sql/` directory.

### 6. Open Power BI Dashboard

Open the `.pbix` file using **Microsoft Power BI Desktop**.

---

# Usage

### SQL Analysis

Run SQL scripts located in the `sql/` folder to generate business insights.

### Python Analysis

Execute the Jupyter notebooks:

```bash
jupyter notebook
```

Run:

- Data Cleaning
- Exploratory Data Analysis
- Customer Segmentation
- ABC Inventory Analysis
- Sales Forecasting

### Power BI Dashboard

Open the dashboard file and interact with:

- Executive Overview
- Customer Analytics
- Inventory Analytics
- Sales Forecast & Trends

Use filters and slicers to explore KPIs across products, customers, categories, cities, and time periods.

---

# Dashboard Screenshots

Add dashboard images inside the following folder:

```text
images/
```

Recommended screenshots:

```text
images/
├── executive_overview.png
├── customer_analytics.png
├── inventory_analytics.png
└── sales_forecast.png
```

These screenshots should showcase:

- Executive Overview
- Customer Analytics Dashboard
- Inventory Analytics Dashboard
- Sales Forecast Dashboard

---

# Business Insights

Some key findings from the analysis include:

- Electronics generated the highest overall revenue among product categories.
- A small percentage of customers contributed a significant share of total sales, highlighting valuable high-value customer segments.
- RFM segmentation identified Champions, Loyal Customers, Big Spenders, Regular Customers, and At-Risk Customers for targeted marketing strategies.
- ABC inventory analysis revealed that a limited number of products accounted for the majority of inventory value, supporting inventory optimization efforts.
- Sales performance varied across regions and cities, indicating opportunities for localized business strategies.
- Monthly sales trends showed seasonal fluctuations that can assist in inventory planning and demand forecasting.
- Revenue and profit analysis identified top-performing products as well as products with high revenue but comparatively lower profit margins.
- The sales forecasting model demonstrated the workflow for predictive analytics and can be enhanced with advanced time-series models for improved accuracy.

---

# Future Improvements

- Implement Prophet or ARIMA for more accurate sales forecasting.
- Develop real-time dashboards using live database connections.
- Build automated ETL pipelines for scheduled data refresh.
- Add customer churn prediction models.
- Implement inventory reorder recommendations.
- Integrate advanced demand forecasting techniques.
- Deploy dashboards to Power BI Service.
- Containerize the project using Docker.
- Add CI/CD workflows with GitHub Actions.
- Expand analysis with additional business KPIs and predictive models.

---

# Author

**Abhishek**

**Computer Science Engineer | Data Analyst | Business Intelligence Enthusiast**

- **GitHub:** https://github.com/yourusername
- **LinkedIn:** https://www.linkedin.com/in/yourprofile
- **Email:** your.email@example.com
