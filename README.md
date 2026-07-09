# 📊 Sales Performance Dashboard | Power BI

An interactive **Sales Performance Dashboard** built using **Power BI Desktop** to analyze sales, profitability, customer behavior, and regional performance. The dashboard enables users to monitor key business metrics through interactive visualizations, DAX measures, and dynamic filtering.

# 📌 Project Overview

The objective of this project is to transform raw retail transaction data into meaningful business insights using Power BI.

The dashboard provides an executive-level overview of sales performance while allowing users to drill down into regional performance, customer profitability, product categories, and sales trends through interactive visualizations.

The project follows standard Business Intelligence practices, including data cleaning, data modeling, DAX calculations, and interactive reporting.

---

# 🎯 Business Objectives

- Monitor overall business performance through key performance indicators.
- Analyze sales and profit trends over time.
- Compare regional sales performance.
- Evaluate category and sub-category profitability.
- Identify high-value customers and low-profit accounts.
- Support business decisions using interactive filtering and drill-down analysis.

---

# 📊 Key Performance Indicators (KPIs)

| KPI | Value |
|------|-------|
| 💰 Total Sales | $2.30M |
| 📈 Total Profit | $286.40K |
| 📦 Total Orders | 5,009 |
| 👥 Total Customers | 793 |
| 🎯 Profit Margin | 12.47% |

---

# 📈 Dashboard Features

### Executive KPI Cards
Displays business performance using:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Profit Margin %

---

### Sales Trend Analysis

Visual:
- Area Chart

Purpose:
- Monitor sales growth over time
- Identify seasonal demand patterns
- Compare yearly performance

---

### Regional Sales Analysis

Visual:
- Clustered Column Chart

Purpose:
- Compare sales across different regions
- Identify top-performing markets

---

### Category Performance

Visual:
- Ribbon Chart

Purpose:
- Compare category rankings across regions
- Track changes in category performance

---

### Profit Contribution Analysis

Visual:
- Waterfall Chart

Purpose:
- Evaluate how each category contributes to total profit
- Identify low-performing business areas

---

### Top Customers Analysis

Visual:
- Horizontal Bar Chart

Purpose:
- Display the Top 10 customers based on total sales
- Support customer relationship management

---

### Monthly Profit Trend

Visual:
- Line Chart

Purpose:
- Track monthly profitability
- Identify seasonal profit fluctuations

---

### Customer Performance Matrix

Visual:
- Matrix

Features:
- Customer Name
- Sales
- Profit
- Quantity

Additional Formatting:
- Data Bars
- Conditional Formatting

---

### Sales Breakdown

Visual:
- Decomposition Tree

Purpose:
- Drill down from Sales → Category → Region → Sub-Category
- Identify root causes behind business performance

---

# 🎛 Interactive Filters

The dashboard includes global slicers for:

- 📅 Order Date
- 🌍 Region
- 📦 Category
- 👥 Segment
- 🚚 Ship Mode

All visuals update dynamically based on the selected filters.

---

# 📐 DAX Measures

```DAX
Total Sales =
SUM(Orders[Sales])

Total Profit =
SUM(Orders[Profit])

Total Orders =
DISTINCTCOUNT(Orders[Order ID])

Total Customers =
DISTINCTCOUNT(Orders[Customer ID])

Total Quantity =
SUM(Orders[Quantity])

Profit Margin % =
DIVIDE([Total Profit],[Total Sales],0)

Average Order Value =
DIVIDE([Total Sales],[Total Orders],0)
```

---

# 🧹 Data Preparation

The dataset was cleaned and transformed using **Power Query**.

Data preparation included:

- Data type validation
- Duplicate removal
- Null value verification
- Date formatting
- Data modeling

---

# 💡 Business Insights

## 1. Regional Performance

The West region generates the highest sales, followed by the East region.

---

## 2. Category Performance

Technology contributes the highest profit, while Furniture generates comparatively lower profitability despite strong sales.

---

## 3. Customer Profitability

Some high-revenue customers contribute lower profit margins, indicating opportunities to review pricing strategies and discount policies.

---

## 4. Seasonal Trends

Sales and profits increase significantly during the final quarter (Q4), highlighting strong seasonal demand.

---

## 5. Interactive Analysis

Users can analyze business performance by filtering data across:

- Region
- Category
- Segment
- Ship Mode
- Order Date

without changing the underlying report.

---

# 🛠 Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel / CSV
- Data Modeling

---

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Modeling
- DAX Calculations
- Dashboard Design
- Business Intelligence
- Data Visualization
- Business Analysis
- Interactive Reporting

---


⭐ If you found this project helpful, please consider giving it a star.
