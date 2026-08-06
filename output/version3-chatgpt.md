# 🛍️ Retail Sales & Inventory Analytics

> An end-to-end Data Analytics project that transforms retail sales and inventory data into actionable business insights using **SQL, Python, Power BI, and Excel**.

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/retail-sales-inventory-analytics?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/retail-sales-inventory-analytics?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

---

# 📖 Overview

Retail businesses generate large volumes of sales and inventory data every day. Without proper analysis, identifying customer behavior, inventory risks, sales trends, and revenue opportunities becomes difficult.

This project demonstrates a complete **Retail Sales & Inventory Analytics solution** that combines **SQL, Python, Power BI, and Excel** to analyze transactional data, optimize inventory management, forecast sales, and provide interactive business dashboards for decision-making.

The project covers the complete analytics workflow:

- Data Cleaning
- SQL Business Analysis
- Exploratory Data Analysis (EDA)
- Customer Segmentation (RFM)
- ABC Inventory Analysis
- Sales Forecasting
- Interactive Power BI Dashboard

---

# 🎯 Objectives

- Analyze retail sales performance
- Understand customer purchasing behavior
- Identify high-value customers
- Optimize inventory management
- Forecast future sales
- Build executive dashboards for business decision-making

---

# ✨ Features

### 📊 Sales Analytics
- Monthly Sales Trend Analysis
- Revenue Analysis
- Product Performance Analysis
- Category-wise Sales
- State-wise Revenue Analysis
- Top Selling Products

### 👥 Customer Analytics
- RFM Customer Segmentation
- Customer Lifetime Value Insights
- Purchase Frequency Analysis
- Customer Revenue Contribution

### 📦 Inventory Analytics
- ABC Inventory Classification
- Inventory Value Analysis
- Warehouse Stock Distribution
- Low Stock Identification
- High Value Inventory Tracking

### 📈 Forecasting
- Sales Forecasting using Linear Regression
- Forecast Visualization
- Trend Analysis

### 📉 Business Intelligence Dashboard
Interactive Power BI dashboard containing:

- Executive Overview
- Customer Analytics
- Inventory Analytics
- Sales Forecast

---

# 🛠️ Technologies Used

| Category | Technologies |
|-----------|--------------|
| Programming | Python |
| Database | MySQL |
| Query Language | SQL |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Dashboard | Power BI |
| ETL & Cleaning | Power Query |
| Measures | DAX |
| Spreadsheet | Microsoft Excel |

---

# 📂 Project Structure

```text
Retail-Sales-Inventory-Analytics/
│
├── data/
│   ├── raw/
│   ├── cleaned/
│   └── processed/
│
├── sql/
│   ├── schema.sql
│   ├── data_import.sql
│   └── analysis_queries.sql
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   ├── customer_segmentation.ipynb
│   ├── inventory_analysis.ipynb
│   └── sales_forecasting.ipynb
│
├── dashboard/
│   └── Retail_Sales_Inventory_Dashboard.pbix
│
├── images/
│   ├── executive_overview.png
│   ├── customer_analytics.png
│   ├── inventory_analytics.png
│   ├── sales_forecast.png
│   └── er_diagram.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 📊 Dashboard Pages

## 1️⃣ Executive Overview

Provides an overall business performance summary.

**KPIs**

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Total Profit
- Inventory Value

---

## 2️⃣ Customer Analytics

Includes customer behavior analysis through:

- RFM Segmentation
- Revenue by Customer Segment
- Customer Purchase Frequency
- Top Customers
- Customer Distribution

---

## 3️⃣ Inventory Analytics

Includes inventory optimization metrics:

- ABC Classification
- Inventory Value Distribution
- Warehouse Analysis
- Stock Level Monitoring
- Inventory Insights

---

## 4️⃣ Sales Forecast

Forecasts future sales using Machine Learning.

Includes:

- Historical Sales
- Forecasted Sales
- Trend Analysis
- Monthly Predictions

---

# 📈 Business Insights

Some key insights generated from the analysis include:

- Electronics generated the highest revenue among all product categories.
- A small percentage of customers contributed a significant portion of total sales.
- Several products generated high revenue but relatively low profit margins.
- Revenue varied significantly across different states.
- Inventory value was concentrated in a limited number of high-value products.
- Monthly sales exhibited seasonal fluctuations.
- Sales forecasting provided estimated future revenue trends for business planning.

---

# 🧠 Machine Learning

Model Used:

- Linear Regression

Purpose:

- Predict future retail sales

Evaluation Metric:

- R² Score

---

# 🗄️ Database Schema

The project uses the following relational tables:

- Customers
- Products
- Sales
- Inventory

The ER Diagram can be added here.

```
images/er_diagram.png
```

---

# 🚀 Installation

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Retail-Sales-Inventory-Analytics.git
```

---

## 2. Navigate to Project Directory

```bash
cd Retail-Sales-Inventory-Analytics
```

---

## 3. Install Required Packages

```bash
pip install -r requirements.txt
```

---

## 4. Configure MySQL Database

- Create the database.
- Run the SQL schema script.
- Import the dataset.
- Execute the analysis queries.

---

## 5. Open Power BI Dashboard

Open:

```
dashboard/Retail_Sales_Inventory_Dashboard.pbix
```

using **Microsoft Power BI Desktop**.

---

# ▶️ Usage

### SQL Analysis

Run the SQL scripts inside the `sql/` folder to perform business analysis.

### Python Analysis

Execute the notebooks in the following order:

1. Data Cleaning
2. EDA
3. Customer Segmentation
4. Inventory Analysis
5. Sales Forecasting

### Dashboard

Open the Power BI dashboard to explore interactive visualizations.

---

# 📸 Screenshots

Add your dashboard screenshots inside the `images/` folder.

Example:

```
images/
│
├── executive_overview.png
├── customer_analytics.png
├── inventory_analytics.png
└── sales_forecast.png
```

Then display them like this:

## Executive Overview

![Executive Overview](images/executive_overview.png)

---

## Customer Analytics

![Customer Analytics](images/customer_analytics.png)

---

## Inventory Analytics

![Inventory Analytics](images/inventory_analytics.png)

---

## Sales Forecast

![Sales Forecast](images/sales_forecast.png)

---

# 📚 Future Improvements

- Implement Prophet-based Sales Forecasting
- Add ARIMA Time Series Forecasting
- Develop Demand Forecasting
- Build Real-Time Dashboard
- Automate ETL Pipeline
- Deploy Dashboard to Power BI Service
- Integrate Cloud Database
- Add Predictive Inventory Replenishment

---

# 🤝 Contributing

Contributions are welcome!

If you would like to improve this project:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Abhishek**

B.Tech Computer Science Engineer

📧 Email: your-email@example.com

🔗 LinkedIn: https://linkedin.com/in/your-profile

💻 GitHub: https://github.com/yourusername

---

## ⭐ If you found this project useful, consider giving it a Star!
