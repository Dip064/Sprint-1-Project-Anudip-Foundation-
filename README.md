#  NIFTY 500 Market Performance Dashboard | Power BI

##  Project Overview

This project is an interactive **Power BI dashboard** built using historical **NIFTY 500** stock market data from **2000 to 2025**. The objective of this project is to transform raw financial data into meaningful business insights through interactive visualizations and dynamic reporting.

The dashboard helps users analyze market trends, compare yearly and monthly performance, monitor trading activity, and understand the overall movement of the NIFTY 500 index.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Project Objectives

- Analyze historical NIFTY 500 market performance.
- Visualize long-term closing price trends.
- Compare yearly and monthly average closing prices.
- Analyze trading volume and market turnover.
- Build an interactive dashboard using Power BI.
- Apply Power BI best practices in data modeling and visualization.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Dataset Information

- **Dataset:** NIFTY 500 Historical Data
- **Source:** National Stock Exchange (NSE)
- **Period Covered:** 2000 – 2025
- **Format:** CSV Files (25 yearly datasets)

### Columns Used

- Date
- Open
- High
- Low
- Close
- Shares Traded
- Turnover

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel (Data Review)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Data Preparation

The following data preparation steps were performed using **Power Query**:

- Imported 25 yearly CSV files
- Combined all files into a single dataset
- Changed data types
- Removed errors
- Checked missing values
- Renamed columns
- Validated data quality

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Calendar Table

A separate **Calendar Table** was created to support time-based analysis.

### Calendar Columns

- Date
- Year
- Month
- Month Number
- Quarter

### Benefits

- Time intelligence
- Dynamic filtering
- Better data modeling
- Improved dashboard performance

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Data Modeling

This project follows the **Star Schema** approach.

### Fact Table

- Fact_NIFTY500

### Dimension Table

- Calendar

### Relationship

- One-to-Many
- Single Cross Filter Direction
- Active Relationship

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  DAX Measures

Some important DAX measures created in this project include:

- Highest Closing Price
- Lowest Closing Price
- Average Closing Price
- Total Shares Traded
- Total Turnover
- Dynamic Dashboard Title

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Dashboard Features

### KPI Cards

- Highest Index Value
- Lowest Index Value
- Average Closing Price
- Total Shares Traded
- Total Turnover

### Interactive Slicers

- Year
- Quarter
- Month

### Visualizations

- Closing Price Trend (Line Chart)
- Year-wise Average Closing Price (Column Chart)
- Month-wise Average Closing Price (Column Chart)
- Shares Traded Trend (Line Chart)
- Turnover Trend (Line Chart)
- Monthly Average Opening vs Closing Price (Line Chart)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Key Insights

- Historical analysis of NIFTY 500 from 2000–2024.
- Long-term market trend visualization.
- Comparison of yearly and monthly market performance.
- Trading activity analysis using Shares Traded and Turnover.
- Interactive filtering using Year, Quarter, and Month slicers.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Dashboard Preview

> *(Add a screenshot of your Power BI dashboard here.)*

Example:

```
Dashboard.png
```

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Skills Demonstrated

- Data Cleaning
- Power Query
- Data Modeling
- Star Schema
- Calendar Table
- DAX
- Dashboard Design
- Data Visualization
- Business Analysis
- Financial Data Analytics

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Future Improvements

- Live NSE API integration
- Forecasting analysis
- Moving Average indicators
- Drill-through pages
- Mobile-friendly dashboard
- Additional financial KPIs

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Learning Outcomes

Through this project, I gained hands-on experience in:

- Building interactive Power BI dashboards
- Working with large historical datasets
- Creating efficient data models
- Writing DAX measures
- Designing professional dashboards
- Presenting business insights using data visualization

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Project Author

**Dipanjan Pramanik**

Aspiring Data Analyst

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Disclaimer

This project was created for **learning and portfolio purposes only**. It should not be considered financial or investment advice.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Data Source & Courtesy

Historical market data provided by the **National Stock Exchange (NSE)**.

Special thanks to the National Stock Exchange for making historical market data available for educational and analytical purposes.
