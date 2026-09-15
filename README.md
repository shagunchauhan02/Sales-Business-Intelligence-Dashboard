# 📊 Sales & Business Intelligence Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-Data%20Analysis-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel-Data%20Preparation-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
  <img src="https://img.shields.io/badge/DAX-KPI%20Analysis-FF8C00?style=for-the-badge" />
</p>

<p align="center">
  <b>Interactive Business Intelligence Dashboard for Sales, Profitability & Performance Analysis</b>
</p>

---

## 🚀 Project Overview

The **Sales & Business Intelligence Dashboard** is an interactive analytics project built using **Power BI, SQL, and Excel** to transform raw sales data into meaningful and actionable business insights.

The dashboard focuses on **sales performance, profitability, product performance, category analysis, regional performance, and time-based trends** through an interactive and executive-friendly reporting solution.

The project demonstrates an end-to-end **Business Intelligence workflow** covering data preparation, transformation, SQL analysis, data modeling, DAX calculations, KPI development, and dashboard visualization.

---

## 🎯 Business Objectives

The main objectives of this project were to:

* 📈 Analyze overall sales and profit performance
* 💰 Monitor important business KPIs
* 🏆 Identify top-performing products
* 📦 Compare category-level performance
* 🌎 Analyze regional sales and profitability
* 📅 Identify sales and profit trends over time
* 🔎 Support data-driven business decision making

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                                           |
| --------------- | ------------------------------------------------- |
| **Power BI**    | Dashboard development & interactive visualization |
| **DAX**         | KPI calculations and business measures            |
| **Power Query** | Data cleaning & transformation                    |
| **SQL**         | Business analysis and data querying               |
| **Excel**       | Data preparation and validation                   |

---

## 📊 Project Workflow

```text
Raw Data
   ↓
Data Cleaning & Preparation
   ↓
Power Query Transformation
   ↓
Data Modeling & Date Table
   ↓
SQL Business Analysis
   ↓
DAX Measures & KPIs
   ↓
Power BI Dashboard
   ↓
Interactive Business Insights
```

---

## 📌 Project Highlights

* **118K+** transaction records analyzed
* **39** business attributes
* **75+** SQL queries developed
* **3** interactive Power BI dashboard pages
* Multiple DAX-based business KPIs
* Product, category, regional and time-based analysis
* Interactive slicers and filters
* Drill-down based analysis
* Executive-level dashboard reporting

---

# 📈 Dashboard

## 1️⃣ Executive Overview

The Executive Overview provides a high-level summary of overall business performance.

### Key Analysis

* Total Sales
* Total Profit
* Total Orders
* Average Order Value
* Profit Margin
* Sales & Profit trends
* Interactive filters
* KPI monitoring

### Dashboard Preview

![Executive Overview](screenshots/01_Executive_Overview.png)

---

## 2️⃣ Product Analysis

The Product Analysis page focuses on product and category-level performance.

### Key Analysis

* Top-performing products
* Product-level sales comparison
* Category performance
* Sales contribution
* Profitability analysis
* Product drill-down
* Performance comparison

### Dashboard Preview

![Product Analysis](screenshots/02_Product_Analysis.png)

---

## 3️⃣ Regional Analysis

The Regional Analysis page evaluates business performance across different regions.

### Key Analysis

* Regional sales comparison
* Regional profitability
* Sales contribution by region
* Regional performance trends
* Interactive filtering
* Region-level comparison

### Dashboard Preview

![Regional Analysis](screenshots/03_Regional_Analysis.png)

---

# 🔑 Key Performance Indicators

The dashboard tracks important business KPIs including:

* 💰 **Total Sales**
* 📈 **Total Profit**
* 🧾 **Total Orders**
* 🛒 **Average Order Value**
* 📊 **Profit Margin**
* 📅 **Sales Trends**
* 🏆 **Product Performance**
* 📦 **Category Performance**
* 🌎 **Regional Performance**

---

# 🧮 DAX Measures

DAX was used to create dynamic business measures and KPIs.

### Total Sales

```DAX
Total Sales = SUM(Orders[Sales])
```

### Total Profit

```DAX
Total Profit = SUM(Orders[Profit])
```

### Total Orders

```DAX
Total Orders = DISTINCTCOUNT(Orders[Order ID])
```

### Average Order Value

```DAX
Average Order Value =
DIVIDE([Total Sales], [Total Orders])
```

### Profit Margin

```DAX
Profit Margin % =
DIVIDE([Total Profit], [Total Sales])
```

---

# 🧹 Data Preparation & Transformation

## Power Query

Power Query was used to prepare the dataset for analysis.

Key activities included:

* Handling missing values
* Correcting data types
* Removing unnecessary fields
* Standardizing data
* Transforming columns
* Preparing analysis-ready data
* Validating transformed data

## SQL Analysis

SQL was used for business-focused analytical queries covering:

* Sales trends
* Product performance
* Revenue analysis
* Customer analysis
* Delivery analysis
* Aggregations
* Business KPIs
* Filtering and grouping
* Performance comparisons

---

# 🎨 Dashboard Features

### 🔹 Interactive Slicers

Users can dynamically filter the dashboard based on relevant business dimensions.

### 🔹 Drill-Down Analysis

Allows users to move from high-level performance to detailed product, category, and regional analysis.

### 🔹 KPI Cards

Provides quick visibility into important business metrics.

### 🔹 Trend Analysis

Helps identify changes in sales and profitability over time.

### 🔹 Dynamic Visualizations

Charts and visuals update according to user selections and filters.

### 🔹 Executive-Friendly Design

The dashboard presents complex business data in a simple and decision-oriented format.

---

# 💡 Business Value

The dashboard converts raw sales data into an interactive Business Intelligence solution that can help users:

* Monitor overall business performance
* Identify high-performing products
* Compare category performance
* Evaluate regional performance
* Track sales trends
* Monitor profitability
* Identify areas requiring further analysis
* Support data-driven decision making

---

# 📄 Project Report

📥 **[View / Download the Project Report](report/Sales_Business_Intelligence_Dashboard.pdf)**

---

# 📁 Repository Structure

```text
Sales-Business-Intelligence-Dashboard/
│
├── README.md
│
├── screenshots/
│   ├── 01_Executive_Overview.png
│   ├── 02_Product_Analysis.png
│   └── 03_Regional_Analysis.png
│
└── report/
    └── Sales_Business_Intelligence_Dashboard.pdf
```

---

# ⭐ Skills Demonstrated

<p align="center">

`Power BI` • `DAX` • `Power Query` • `SQL` • `Excel`

`Data Cleaning` • `Data Transformation` • `Data Modeling`

`KPI Development` • `Business Intelligence` • `Data Visualization`

`Business Analysis` • `Dashboard Development`

</p>

---

# 🔮 Future Enhancements

Potential future improvements include:

* 🔄 Automated data refresh
* 📊 Additional business KPIs
* 🔮 Sales forecasting
* 👥 Customer segmentation
* 💰 Advanced profitability analysis
* 🗄️ Live database connectivity

---

**Skills:** SQL • Python • Power BI • Excel • Data Analytics • Business Intelligence

---

<p align="center">
  ⭐ If you found this project useful, consider giving the repository a star!
</p>
