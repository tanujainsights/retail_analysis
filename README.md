# 🛍️ Retail Sales Analysis | Python + SQL + Power BI

An end-to-end **Retail Sales Analysis project** using **Python, SQL, Excel, and Power BI** to clean, analyze, visualize, and extract actionable insights from retail sales data.

The project focuses on understanding **sales performance, product performance, customer behavior, and revenue trends** to support data-driven business decisions.

---

## 📌 Project Overview

Retail businesses generate large amounts of transactional data. This project analyzes retail sales data to identify important patterns and answer practical business questions such as:

* Which products generate the highest sales?
* Which categories perform the best?
* Who are the most valuable customers?
* How do sales change over time?
* What are the major sales trends?
* Which products or categories require more attention?
* What business actions can improve sales performance?

The project follows an end-to-end analytics workflow:

**Raw Data → Data Cleaning → Exploratory Data Analysis → SQL Analysis → Visualization → Power BI Dashboard → Business Insights**

---

## 🛠️ Tools & Technologies

| Tool                 | Purpose                              |
| -------------------- | ------------------------------------ |
| **Python**           | Data cleaning, EDA and visualization |
| **Pandas**           | Data manipulation and analysis       |
| **NumPy**            | Numerical operations                 |
| **Matplotlib**       | Data visualization                   |
| **Seaborn**          | Statistical visualization            |
| **PostgreSQL**       | SQL analysis and business queries    |
| **Excel**            | Data preparation and validation      |
| **Power BI**         | Interactive dashboard and reporting  |
| **Jupyter Notebook** | Python analysis environment          |

---

## 📂 Project Structure

```text
retail_analysis/
│
├── retail_analysis.ipynb
│       └── Python data cleaning, EDA & visualization
│
├── retail_analysis.sql
│       └── SQL queries for business analysis
│
├── retail_sales_dataset.csv
│       └── Raw retail sales dataset
│
├── retail_sales_clean data.xlsx
│       └── Cleaned dataset
│
├── retail_sales_dashboard.pbix
│       └── Power BI interactive dashboard
│
├── LICENSE
│
└── README.md
```

---

## 🔄 Data Analysis Workflow

### 1. Data Cleaning

The raw dataset was examined and cleaned to improve data quality.

Key steps included:

* Checking the dataset structure
* Identifying missing values
* Checking duplicate records
* Removing duplicate transactions
* Checking data types
* Converting date columns into appropriate formats
* Validating numerical columns
* Preparing the cleaned dataset for analysis

---

### 2. Exploratory Data Analysis

Python was used to explore the dataset and identify important patterns.

Libraries used:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

The analysis includes:

* Sales distribution
* Product performance
* Category performance
* Customer analysis
* Sales trends
* Correlation analysis
* Distribution analysis
* Business-oriented visualizations

---

### 3. SQL Analysis

PostgreSQL was used to answer business questions using SQL.

Examples include:

#### Top 10 Products by Sales

```sql
SELECT 
    product_name,
    SUM(total_sales) AS sales
FROM retail_sales
GROUP BY product_name
ORDER BY sales DESC
LIMIT 10;
```

#### Total Sales

```sql
SELECT 
    SUM(total_sales) AS total_sales
FROM retail_sales;
```

#### Number of Transactions

```sql
SELECT 
    COUNT(*) AS total_transactions
FROM retail_sales;
```

#### Sales by Product

```sql
SELECT 
    product_name,
    SUM(total_sales) AS total_sales
FROM retail_sales
GROUP BY product_name
ORDER BY total_sales DESC;
```

---

## 📊 Power BI Dashboard

The Power BI dashboard converts the analysis into an interactive business reporting solution.

The dashboard can be used to analyze:

* Total Sales
* Product Performance
* Category Performance
* Customer Trends
* Sales Distribution
* Revenue Trends
* Top-performing products

### Dashboard Preview

> Add your Power BI dashboard screenshot here.

```markdown
![Retail Sales Dashboard](dashboard.png)
```

---

## 💡 Key Business Insights

The analysis helps identify:

* High-performing products that contribute significantly to overall sales.
* Products with relatively lower sales that may require promotional strategies.
* Differences in performance across product categories.
* Customer purchasing patterns.
* Sales trends that can support business planning.
* Opportunities to improve product and customer targeting.

---

## 📈 Business Recommendations

Based on the analysis, businesses can:

1. Focus marketing efforts on high-performing products.
2. Identify underperforming products and evaluate pricing or promotional strategies.
3. Use customer purchasing behavior to create targeted campaigns.
4. Monitor sales trends to improve inventory planning.
5. Use Power BI dashboards for continuous performance monitoring.
6. Prioritize products and categories with strong revenue potential.

---

## 🎯 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas
* NumPy
* SQL
* PostgreSQL
* Excel
* Power BI
* Data Visualization
* Business Analysis
* KPI Analysis
* Data Storytelling

---

## 👩‍💻 Author

**Tanuja**

Aspiring Data Analyst | Python | SQL | Power BI | Excel

GitHub:
https://github.com/tanujainsights

---

## 📜 License

This project is licensed under the MIT License.
