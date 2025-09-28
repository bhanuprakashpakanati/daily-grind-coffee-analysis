# Daily Grind Coffee Shop - Data Analysis Project

## 📊 Project Overview
This project involves a comprehensive data analysis of sales data for "The Daily Grind" coffee shop, covering transaction data from March 2024 to October 2024. The analysis was conducted using SQL Server Management Studio (SSMS) to extract actionable insights for improving profitability, customer satisfaction, and operational efficiency.

## 🎯 Business Objectives
- Transition from intuition-based to data-driven decision making
- Optimize menu offerings, staffing schedules, and pricing strategies
- Understand customer behavior patterns and peak business hours
- Analyze sales trends and product performance

## 📁 Project Structure
daily-grind-coffee-analysis/
│
├── Client Requirements Document.pdf
├── SQL.sql
└── README.md

## 📋 Data Source
- **File:** `coffee.csv`
- **Period:** March 2024 - October 2024
- **Type:** Point-of-Sale (POS) transaction data
- **Key Fields:** 
  - `hour_of_day`, `Time_of_Day` (Morning/Afternoon/Night)
  - `coffee_name` (Product)
  - `money` (Sale Price)
  - `cash_type` (Payment Method)
  - `Weekday`, `Month_name`, `Date`

## 🔍 Analysis Areas

### A. Sales & Revenue Analysis
- Overall performance metrics (Total Revenue, Orders, AOV)
- Monthly and weekly revenue trends
- Hourly and time-of-day performance

### B. Product Performance & Menu Optimization
- Best and worst selling products
- Pricing analysis and revenue contribution
- Premium vs. budget product performance

### C. Customer Behavior & Peak Hours
- Busiest transaction hours
- Weekday vs. weekend patterns
- Customer purchasing behavior

### D. Pricing & Payment Analysis
- Payment method distribution
- Price change tracking for key products

## 🛠️ Technical Implementation
- **Tool:** SQL Server Management Studio (SSMS)
- **Language:** SQL (T-SQL)
- **Key Features:** 
  - Complex aggregations and window functions
  - CTE (Common Table Expressions)
  - Trend analysis and pattern recognition
  - Data quality handling for time anomalies

## 📈 Key Deliverables
1. Complete SQL script with all analytical queries
2. Analysis covering all business questions from CRD
3. Ready-to-use queries for visualization in Power BI/Excel
4. Identification of price change dates and patterns

## 🚀 Getting Started
1. Clone this repository
2. Execute the `SQL.sql` script in SSMS
3. Connect to your coffee sales database
4. Run individual queries to generate specific insights

## 💡 Key Insights Generated
- Monthly revenue trends and growth patterns
- Peak business hours and seasonal variations
- Product performance rankings and pricing strategies
- Customer behavior differences between weekdays and weekends

## 📊 Visualization Ready
The SQL queries are structured to easily export results to visualization tools like:
- Power BI
- Excel
- Tableau
- Other BI platforms

## 🔮 Future Enhancements
- Integration with real-time data feeds
- Predictive analytics for demand forecasting
- Customer segmentation analysis
- Seasonal trend modeling

---
