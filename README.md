# 🚗 Automobile Market Analysis using Python, SQL, Statistics & Power BI

## 📌 Project Overview

This project presents an end-to-end Data Analytics solution for analyzing a large Automobile Market dataset containing over **559,000 vehicle sales records**.

The project demonstrates the complete data analytics lifecycle, including:

- Data Understanding
- Data Cleaning & Feature Engineering
- Exploratory Data Analysis (EDA)
- Business Intelligence Analysis
- Inferential Statistics & Hypothesis Testing
- SQL Business Analysis
- Interactive Power BI Dashboard
- Business Insights & Recommendations

The objective of this project is to identify the factors affecting vehicle resale value, understand market trends, analyze seller and regional performance, and provide data-driven business recommendations.

---

# 🎯 Project Objectives

- Clean and preprocess the automobile sales dataset.
- Handle missing values and inconsistent records.
- Engineer new analytical features.
- Perform Exploratory Data Analysis.
- Validate business assumptions using statistical testing.
- Solve business problems using SQL.
- Develop interactive dashboards using Microsoft Power BI.
- Generate actionable business insights.

---

# 📂 Dataset Information

The dataset contains approximately **559,000 vehicle sales records** with the following information:

- Manufacturing Year
- Make
- Model
- Trim
- Body Type
- Transmission
- VIN
- State
- Vehicle Condition
- Odometer
- Exterior Color
- Interior Color
- Seller
- Manheim Market Report (MMR)
- Selling Price
- Sale Date

---

# 🛠 Tech Stack

## Programming

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Database

- SQLite / MySQL

## Business Intelligence

- Microsoft Power BI
- DAX

## Development Environment

- Jupyter Notebook
- VS Code

---

# 📁 Project Structure

```
Automobile-Market-Analysis/
│
├── Dataset/
│   ├── raw_dataset.csv
│   ├── cleaned_dataset.csv
│
├── Python/
│   ├── Data Cleaning.ipynb
│   ├── EDA.ipynb
│   ├── Business Intelligence.ipynb
│   ├── Hypothesis Testing.ipynb
│   ├── SQL Queries.ipynb
│
├── Power BI/
│   ├── vehicle_sales.pbix
│
│
├── Images/
│   ├── Dashboard1.png
│   ├── Dashboard2.png
│   ├── Dashboard3.png
│   ├── Dashboard4.png
│   ├── Dashboard5.png
│
└── README.md
```

---

# 🔄 Project Workflow

```
Dataset Collection
        │
        ▼
Data Understanding
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Business Intelligence Analysis
        │
        ▼
Inferential Statistics
        │
        ▼
SQL Business Analysis
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights
```

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Corrected incorrect data types
- Converted Sale Date into datetime format
- Outlier Detection
- Data Validation
- Feature Engineering

---

# ⚙ Feature Engineering

The following new features were created:

| Feature | Formula |
|----------|----------|
| Vehicle Age | Sale Year − Manufacturing Year |
| Price Difference | Selling Price − MMR |
| Price Ratio | Selling Price ÷ MMR |
| Sale Month | Month(Sale Date) |
| Sale Quarter | Quarter(Sale Date) |
| Sale Weekday | Weekday(Sale Date) |

---

# 📊 Exploratory Data Analysis

EDA was performed to understand:

- Missing Values
- Outliers
- Distribution Analysis
- Correlation Analysis
- Monthly Sales Trend
- Brand Analysis
- Seller Analysis
- Geographic Analysis
- Transmission Analysis
- Body Type Analysis
- Vehicle Condition Analysis

Visualizations included:

- Histograms
- Boxplots
- Scatter Plots
- Line Charts
- Bar Charts
- Pie Charts
- Heatmaps

---

# 📈 Business Intelligence Analysis

The following KPIs were generated:

- Total Vehicles
- Total Revenue
- Average Selling Price
- Average MMR
- Average Vehicle Age
- Average Price Ratio
- Premium Vehicles
- Premium Sellers

Business questions answered:

- Which brands dominate the market?
- Which states generate the highest revenue?
- Which sellers generate the highest revenue?
- Which brands sell above MMR?
- Which body types dominate premium sales?
- Which transmission type dominates?

---

# 📉 Statistical Analysis

The following statistical tests were conducted:

- Shapiro-Wilk Test
- Mann-Whitney U Test
- One-Way ANOVA
- Kruskal-Wallis Test
- Spearman Correlation
- Effect Size Analysis

### Major Hypotheses

- Does transmission affect selling price?
- Does vehicle condition affect selling price?
- Does vehicle age affect selling price?
- Does odometer affect selling price?
- Are certain brands sold above MMR?
- Do body types influence selling price?
- Does transmission affect resale value?
- Are premium brands concentrated in specific states?

---

# 💾 SQL Business Analysis

SQL queries were developed to calculate:

- KPIs
- Revenue Analysis
- Monthly Sales
- Top Brands
- Top Sellers
- Premium Vehicle Analysis
- State-wise Analysis
- Transmission Analysis
- Body Type Analysis
- Ranking Functions
- Window Functions

---

# 📊 Power BI Dashboard

The project contains **5 interactive dashboard pages**.

## Dashboard 1

### Executive Dashboard

Features

- KPI Cards
- Monthly Sales Trend
- Brand Analysis
- State Map
- Transmission Analysis
- Body Distribution

---

## Dashboard 2

### Pricing & Resale Value Analysis

Features

- Selling Price vs MMR
- Average Selling Price by Brand
- Price Difference
- Price Ratio
- Odometer Analysis

---

## Dashboard 3

### Vehicle Performance & Market Intelligence

Features

- Vehicle Age Analysis
- Vehicle Condition
- Body Type Analysis
- Transmission Analysis
- Odometer Analysis

---

## Dashboard 4

### Seller & Market Intelligence

Features

- Seller Performance
- Premium Sellers
- Revenue by State
- Premium Brands
- Premium Models
- Premium Body Types

---

## Dashboard 5

### Executive Insights & Recommendations

Includes

- Key Business Insights
- Business Recommendations
- Technology Stack

---

# 📌 Key Findings

- Approximately **559K** vehicles were analyzed.
- Vehicles sold on average **$158 below MMR**.
- Automatic transmission dominated vehicle sales.
- Mercedes-Benz, BMW and Lexus recorded the highest average selling prices.
- Vehicle age negatively impacts resale value.
- Higher mileage decreases selling price.
- Better vehicle condition significantly improves resale value.
- Florida and California showed strong premium vehicle demand.

---

# 💡 Business Recommendations

- Increase inventory of low-mileage vehicles.
- Expand premium brands in high-demand states.
- Use MMR as a pricing benchmark.
- Improve pricing strategy using market analytics.
- Prioritize well-maintained vehicles.
- Focus marketing efforts on premium regions.

---

# 📷 Dashboard Preview

> Add screenshots of all five Power BI dashboard pages here.

Example:

```
images/dashboard1.png
images/dashboard2.png
images/dashboard3.png
images/dashboard4.png
images/dashboard5.png
```

---

# 🚀 Future Scope

- Machine Learning Price Prediction
- Vehicle Demand Forecasting
- Customer Segmentation
- Dealer Recommendation System
- Cloud Deployment
- Real-Time Dashboard

---

# 👨‍💻 Author

**Tamanna Dagar**

Data Analytics Portfolio Project

Skills Demonstrated

- Python
- SQL
- Statistics
- Power BI
- Data Cleaning
- Exploratory Data Analysis
- Business Intelligence
- Dashboard Development
- Data Visualization

---

# ⭐ If you found this project useful, consider giving it a star!
