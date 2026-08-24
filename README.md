# 📊 Superstore Sales Analytics

> An end-to-end Exploratory Data Analysis project to uncover sales, profitability, customer, regional and product-level insights from the Superstore dataset.

---

## 🚀 Project Overview

This project analyzes **9,994 Superstore transactions** using Python to understand:

- 📈 Sales performance
- 💰 Profitability
- 🌎 Regional & state performance
- 👥 Customer segments
- 📦 Category & sub-category performance
- 🚚 Shipping patterns
- 🎯 Discount impact
- 📅 Monthly sales & profit trends

The goal is to transform raw transactional data into **actionable business insights**.

---

## 📸 Project Highlights

![Sales by Category](images/sales_by_category.png)

![Profit by Region](images/profit_by_region.png)

![Correlation Heatmap](images/correlation_heatmap.png)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 🐍 Python | Data analysis |
| 🐼 Pandas | Data cleaning & analysis |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical visualization |
| 📓 Jupyter Notebook | Analysis & documentation |

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Preparation
- Checked dataset structure and data types
- Converted `Order Date` and `Ship Date` to datetime
- Checked missing values
- Checked duplicate records
- Created additional time-based features

### 2. Exploratory Data Analysis
Analyzed:

- Total Sales
- Total Profit
- Average Profit
- Quantity
- Discount
- Category performance
- Regional performance
- Customer segments
- State-level performance
- Sub-category performance
- Shipping modes
- Monthly trends

### 3. Correlation Analysis

Analyzed the relationship between:

`Sales | Quantity | Discount | Profit`

---

## 💡 Key Business Insights

### 🏆 Category Performance
**Technology** generated the highest overall Sales and Profit among the three categories.

### 🌎 Regional Performance
The **West region** was the strongest performer in terms of both Sales and Profit.

### 👥 Customer Segments
The **Consumer segment** contributed the highest Sales and Profit.

### 📍 State Performance
**California** was the leading state in both Sales and Profit.

### 📦 Sub-Category Performance
**Phones** generated the highest Sales, while **Copiers** generated the highest Profit.

### 🚚 Shipping
**Standard Class** generated the highest Sales among the shipping modes.

### 💰 Discount Impact
Discount showed a **negative correlation with Profit (-0.22)**, suggesting that higher discounting can negatively affect profitability.

### 📈 Sales & Profit Relationship
Sales and Profit showed a **moderate positive correlation (0.48)**, indicating that higher sales generally tend to be associated with higher profit.

---

## 📊 Important Findings

| Metric | Finding |
|--------|---------|
| Dataset Size | 9,994 rows × 22 columns |
| Missing Values | 0 |
| Duplicate Rows | 0 |
| Top Category | Technology |
| Top Region | West |
| Top Segment | Consumer |
| Top State | California |
| Top Sales Sub-Category | Phones |
| Top Profit Sub-Category | Copiers |
| Sales ↔ Profit | 0.48 |
| Discount ↔ Profit | -0.22 |

---

## 📁 Project Structure

```text
Superstore-Sales-Analytics/
│
├── datasets/
│   └── raw/
│
├── notebooks/
│   └── Superstore_Sales_Analysis.ipynb
│
├── images/
│   ├── sales_by_category.png
│   ├── profit_by_region.png
│   └── correlation_heatmap.png
│
├── src/
│
└── README.md
