# Customer-Behaviour-Analysis

# Customer Shopping Behavior Analysis

## Overview

This project provides an end-to-end data analytics workflow to understand consumer shopping habits. The goal is to derive actionable insights regarding purchase patterns, demographic segments, and the impact of marketing strategies such as discounts and subscriptions on sales.

---

## Dataset

The analysis is based on the **customer_shopping_behavior.xls** dataset, which contains information on approximately **3,900 customers**, including:

* Age
* Gender
* Product Category
* Purchase Amount
* Subscription Status
* Review Ratings
* Shopping Behavior Metrics

---

## Tools Used

| Tool            | Purpose                            |
| --------------- | ---------------------------------- |
| Python (Pandas) | Data Cleaning & EDA                |
| MySQL           | Database Management & SQL Analysis |
| Power BI        | Dashboard Creation & Visualization |

---

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.xls
│
├── Python/
│   └── notebooks_customer_behaviour(1).ipynb
│
├── SQL/
│   └── customer_behaviourqueries.sql
│
├── PowerBI/
│   └── Customer_behaviourDashboard.pbix
│
└── README.md
```

---

## Project Steps

### 1. Exploratory Data Analysis (EDA)

* Loaded the dataset using Python.
* Handled missing values in review ratings.
* Standardized column names and data formats.
* Explored customer demographics and purchase patterns.

### 2. Data Modeling

* Created derived features such as:

  * `age_group`
  * `purchase_frequency_days`
* Improved customer segmentation and analysis.

### 3. Database Integration

* Loaded the cleaned dataset into a MySQL database.
* Structured data for efficient querying and reporting.

### 4. SQL Analysis

* Analyzed revenue contribution across customer groups.
* Evaluated discount effectiveness.
* Performed customer segmentation analysis.
* Generated business-focused insights using SQL queries.

### 5. Dashboard Development

* Built an interactive Power BI dashboard.
* Created KPIs and visual reports.
* Added filters and slicers for dynamic exploration.


## Dashboard Features

* Total Revenue Analysis
* Category-wise Sales Performance
* Customer Segmentation
* Subscription Status Analysis
* Discount Impact Analysis
* Age Group Revenue Contribution
* Interactive Filters & Slicers

---

## Results

### Key Findings

* Discount effectiveness varies significantly across product categories.
* Customers were segmented into **New**, **Returning**, and **Loyal** groups, revealing distinct purchasing behaviors.
* Subscription status has a measurable impact on customer spending patterns.
* Different age groups contribute differently to overall revenue.

### Recommendations

* Optimize discount strategies based on product category performance.
* Develop targeted campaigns for high-value customer segments.
* Increase subscription adoption through personalized offers.
* Focus marketing efforts on high-revenue age groups.

---


## Author

**Charak Karle**

Aspiring Data Analyst | SQL | Python | Power BI | Excel
