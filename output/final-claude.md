# Retail Sales & Inventory Analytics

## Project Overview
Retail Sales & Inventory Analytics is an end-to-end data analytics project that analyzes retail sales, customer behavior, inventory performance, and future sales trends. It combines SQL, Python, Machine Learning, and Power BI to transform raw retail data into actionable business insights that support data-driven decision-making. The project simulates a real-world analytics workflow — from data extraction and cleaning to modeling and dashboard reporting — and is intended to demonstrate practical, job-ready analytics skills.

## Key Features
- SQL-based business analysis for querying and extracting key retail metrics
- Exploratory Data Analysis (EDA) to uncover patterns and trends in sales data
- Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis
- ABC Inventory Analysis to classify inventory by value and priority
- Sales Forecasting using Linear Regression
- Product profitability analysis
- Customer purchasing behavior analysis
- Revenue and profit analysis
- Interactive Power BI Dashboard with multiple analytical views

## Technologies Used
| Category | Tools |
|---|---|
| Database | SQL, MySQL |
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Business Intelligence | Power BI, DAX |
| Reporting | Excel |

## Project Architecture
The project follows a structured analytics pipeline:

```
Raw Retail Data
      │
      ▼
Data Cleaning & Preparation (Python, Excel)
      │
      ▼
SQL Database (MySQL) — Business Queries & Analysis
      │
      ▼
Exploratory Data Analysis (Python: Pandas, NumPy, Matplotlib)
      │
      ▼
Advanced Analysis
   ├── RFM Customer Segmentation
   ├── ABC Inventory Analysis
   └── Sales Forecasting (Scikit-learn — Linear Regression)
      │
      ▼
Power BI Dashboard (DAX Measures & Interactive Reporting)
      │
      ▼
Business Insights & Recommendations
```

## Installation
1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/retail-sales-inventory-analytics.git
   cd retail-sales-inventory-analytics
   ```
2. Set up a Python environment and install dependencies
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. Set up the MySQL database
   - Create a new MySQL database
   - Import the provided SQL scripts/data files to load the retail dataset
4. Open the Power BI file
   - Launch `Retail_Analytics_Dashboard.pbix` in Power BI Desktop
   - Update the data source connection to point to your local MySQL database

## Usage
1. **SQL Analysis**: Run the queries in the `/sql` folder to explore business metrics such as revenue, top-selling products, and state-wise performance.
2. **Python Analysis**: Open the notebooks in `/notebooks` to run EDA, RFM segmentation, ABC inventory analysis, and the sales forecasting model.
3. **Power BI Dashboard**: Open the `.pbix` file to interact with the dashboard — filter by date, region, category, or customer segment to explore insights visually.
4. **Reports**: Refer to `/reports` for exported summaries and Excel-based supporting analysis.

## Dashboard Screenshots
> Add screenshots of each dashboard page below to showcase the project visually.

| Page | Preview |
|---|---|
| Executive Overview | `screenshots/executive_overview.png` |
| Customer Analytics | `screenshots/customer_analytics.png` |
| Inventory Analytics | `screenshots/inventory_analytics.png` |
| Sales Forecast & Trends | `screenshots/sales_forecast_trends.png` |

## Business Insights
- **Electronics** generated the highest revenue among all product categories.
- RFM Analysis segmented customers into **Champions, Loyal Customers, Big Spenders, Regular Customers, and At-Risk Customers**, enabling targeted retention and marketing strategies.
- ABC Inventory Analysis classified products into **A, B, and C classes** based on inventory value, helping prioritize stock management and reduce holding costs.
- Sales forecasting using **Linear Regression** provided a data-driven basis for anticipating future demand.
- Revenue trends showed notable **variation across months and states**, highlighting seasonal and regional performance differences.
- Analysis of customer purchasing behavior and product profitability offered actionable recommendations to support pricing, inventory, and marketing decisions.

## Future Improvements
- Incorporate advanced forecasting models (e.g., ARIMA, Prophet, or XGBoost) for improved prediction accuracy
- Automate the ETL pipeline for real-time or scheduled data refresh
- Deploy the dashboard to Power BI Service for wider accessibility
- Add a recommendation engine for cross-selling and upselling opportunities
- Expand customer segmentation with clustering techniques (e.g., K-Means)

## Author
**[Your Name]**
Data Analyst | Business Intelligence Enthusiast

- LinkedIn: [your-linkedin-url]
- GitHub: [your-github-url]
- Email: [your-email@example.com]
