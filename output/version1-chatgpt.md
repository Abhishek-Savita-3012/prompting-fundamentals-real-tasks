# 🛒 Retail Sales & Inventory Analytics

> A complete end-to-end Retail Analytics project that transforms raw retail data into actionable business insights using **SQL, Python, Power BI, and Excel**.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![SQL](https://img.shields.io/badge/MySQL-Database-orange?logo=mysql)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📌 Project Overview

Retail businesses generate huge amounts of sales and inventory data every day. Without proper analysis, valuable business opportunities remain hidden.

This project demonstrates a complete Retail Analytics workflow—from raw data cleaning to interactive dashboard creation—helping businesses understand sales performance, customer behavior, inventory optimization, and future sales trends.

The project combines:

- SQL for business analysis
- Python for data cleaning and analytics
- Machine Learning for sales forecasting
- Power BI for interactive dashboards
- Excel for reporting and validation

---

# 🎯 Project Objectives

The primary objectives of this project are:

- Analyze retail sales performance
- Understand customer purchasing behavior
- Identify high-value customers using RFM Analysis
- Perform ABC Inventory Classification
- Forecast future sales
- Optimize inventory management
- Build an executive-level Power BI dashboard

---

# 🚀 Tech Stack

| Technology | Purpose |
|------------|----------|
| MySQL | Data Storage & SQL Analysis |
| SQL | Business Queries |
| Python | Data Cleaning & Analytics |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Scikit-learn | Sales Forecasting |
| Excel | Data Validation |
| Power BI | Interactive Dashboard |
| DAX | KPI Calculations |
| Power Query | Data Transformation |

---

# 📂 Project Structure

```text
Retail-Sales-Inventory-Analytics/
│
├── data/
│   ├── customers.csv
│   ├── products.csv
│   ├── sales.csv
│   └── inventory.csv
│
├── sql/
│   ├── database.sql
│   ├── business_queries.sql
│   └── views.sql
│
├── notebooks/
│   ├── eda.ipynb
│   ├── rfm_analysis.ipynb
│   ├── abc_analysis.ipynb
│   └── sales_forecasting.ipynb
│
├── powerbi/
│   └── Retail Analytics Dashboard.pbix
│
├── dashboard_screenshots/
│   ├── executive_overview.png
│   ├── customer_analytics.png
│   ├── inventory_analytics.png
│   └── sales_forecast.png
│
├── reports/
│
├── README.md
└── requirements.txt
```

---

# 📊 Dataset Information

The project uses four primary datasets:

## Customers

| Column |
|---------|
| CustomerID |
| CustomerName |
| Gender |
| Age |
| City |
| State |
| JoinDate |

---

## Products

| Column |
|---------|
| ProductID |
| ProductName |
| Category |
| SubCategory |
| CostPrice |
| SellingPrice |

---

## Sales

| Column |
|---------|
| OrderID |
| OrderDate |
| CustomerID |
| ProductID |
| Quantity |
| Discount |

---

## Inventory

| Column |
|---------|
| ProductID |
| Warehouse |
| StockQuantity |
| ReorderLevel |
| InventoryValue |

---

# 🔍 SQL Business Analysis

The SQL phase answers important business questions including:

- Total Revenue
- Monthly Sales Trend
- Yearly Revenue
- Best Selling Products
- Top Customers
- Category-wise Sales
- Profit Analysis
- Inventory Performance
- Revenue by State
- Revenue by City

---

# 🐍 Python Analytics

Python was used for:

- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Feature Engineering
- Exploratory Data Analysis
- Customer Segmentation
- Inventory Analysis
- Sales Forecasting

Libraries used:

```python
Pandas
NumPy
Matplotlib
Scikit-learn
```

---

# 📈 Customer Segmentation (RFM Analysis)

Customers were segmented into:

- 🏆 Champions
- 💚 Loyal Customers
- 💙 Big Spenders
- 🟢 Regular Customers
- ❤️ At Risk Customers

The analysis helps businesses:

- Improve customer retention
- Launch targeted marketing campaigns
- Increase repeat purchases

---

# 📦 ABC Inventory Analysis

Products were classified into:

| Category | Description |
|----------|-------------|
| A | High-value inventory requiring strict monitoring |
| B | Moderate-value inventory |
| C | Low-value inventory requiring minimal control |

This helps businesses:

- Reduce inventory costs
- Prevent stock shortages
- Improve warehouse efficiency

---

# 🤖 Sales Forecasting

A Linear Regression model was developed to forecast future sales.

Workflow:

- Feature Engineering
- Model Training
- Prediction
- Performance Evaluation

Evaluation Metric:

- R² Score

---

# 📊 Power BI Dashboard

The dashboard contains four interactive pages.

## 1️⃣ Executive Overview

Features:

- Revenue KPI
- Profit KPI
- Orders KPI
- Customer KPI
- Sales Trend
- Revenue by State
- Revenue by Category
- Revenue by City Map

---

## 2️⃣ Customer Analytics

Includes:

- Customer Segmentation
- RFM Analysis
- Repeat Customers
- Customer Distribution
- Segment Contribution

---

## 3️⃣ Inventory Analytics

Includes:

- ABC Classification
- Inventory Value
- Warehouse Performance
- Reorder Analysis
- Stock Distribution

---

## 4️⃣ Sales Forecast & Trends

Includes:

- Monthly Sales Trend
- Forecasted Sales
- Revenue Growth
- Seasonal Analysis
- Future Sales Projection

---

# 📸 Dashboard Preview

> Replace these placeholders with your actual dashboard screenshots.

## Executive Overview

![Executive Overview](dashboard_screenshots/executive_overview.png)

---

## Customer Analytics

![Customer Analytics](dashboard_screenshots/customer_analytics.png)

---

## Inventory Analytics

![Inventory Analytics](dashboard_screenshots/inventory_analytics.png)

---

## Sales Forecast

![Sales Forecast](dashboard_screenshots/sales_forecast.png)

---

# 📈 Key Business Insights

Some major findings from the analysis include:

- Electronics generated the highest overall revenue.
- A small percentage of customers contributed a significant share of total sales.
- Several products generated high revenue but relatively low profit margins.
- Revenue varied considerably across different states and cities.
- Inventory value was heavily concentrated in Category A products.
- Sales showed clear monthly fluctuations, indicating seasonality.
- Linear Regression achieved limited forecasting accuracy, suggesting advanced time-series models (such as ARIMA or Prophet) could improve predictions.

---

# 💡 Business Recommendations

- Improve retention strategies for At Risk customers.
- Increase promotional campaigns for high-profit products.
- Monitor Category A inventory more frequently.
- Optimize reorder levels using demand forecasting.
- Introduce personalized marketing based on customer segments.
- Consider advanced forecasting models for improved prediction accuracy.

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Retail-Sales-Inventory-Analytics.git
```

Move into the project directory:

```bash
cd Retail-Sales-Inventory-Analytics
```

Install required packages:

```bash
pip install -r requirements.txt
```

---

# ▶️ Usage

1. Import datasets into MySQL.
2. Execute SQL scripts.
3. Run Python notebooks.
4. Open the Power BI dashboard.
5. Explore interactive insights.

---

# 📌 Future Improvements

- ARIMA Forecasting
- Facebook Prophet Forecasting
- XGBoost Sales Prediction
- Customer Lifetime Value Prediction
- Inventory Optimization Model
- Automated ETL Pipeline
- Cloud Deployment

---

# 🤝 Contributing

Contributions are welcome.

If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Abhishek**

B.Tech Computer Science Engineering

Passionate about:

- Data Analytics
- Business Intelligence
- SQL
- Python
- Power BI
- Machine Learning

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
