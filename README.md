# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using a dataset of **3,900 customer transactions**. The objective is to discover customer purchasing patterns, product preferences, spending habits, and subscription trends to help businesses make data-driven decisions.

The project includes:
- Data Cleaning & Feature Engineering using Python
- Data Storage & Business Analysis using PostgreSQL
- Interactive Dashboard Development using Power BI

---

## 🎯 Objectives

- Analyze customer purchasing behavior
- Identify high-value customer segments
- Compare subscriber and non-subscriber spending
- Discover top-selling and highest-rated products
- Generate actionable business recommendations
- Visualize insights through an interactive Power BI dashboard

---

## 📂 Dataset Information

- **Total Records:** 3,900
- **Columns:** 18

### Features
- Customer Demographics
  - Age
  - Gender
  - Location
  - Subscription Status

- Purchase Details
  - Item Purchased
  - Category
  - Purchase Amount
  - Season
  - Size
  - Color

- Shopping Behavior
  - Discount Applied
  - Promo Code Used
  - Previous Purchases
  - Frequency of Purchases
  - Review Rating
  - Shipping Type

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Data Cleaning & Feature Engineering |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| PostgreSQL | Database & SQL Analysis |
| SQL | Business Queries |
| Power BI | Dashboard & Visualization |
| Git & GitHub | Version Control |

---

## 🔄 Project Workflow

```
Dataset
   │
   ▼
Data Cleaning (Python)
   │
   ▼
Feature Engineering
   │
   ▼
Load Clean Data into PostgreSQL
   │
   ▼
Business Analysis using SQL
   │
   ▼
Power BI Dashboard
   │
   ▼
Business Insights & Recommendations
```

---

## 🧹 Data Preprocessing

- Imported dataset using Pandas
- Checked data types and summary statistics
- Handled missing values
- Filled missing review ratings using median values
- Renamed columns to snake_case
- Created Age Groups
- Created Purchase Frequency feature
- Removed redundant columns
- Loaded cleaned dataset into PostgreSQL

---

## 📊 SQL Business Analysis

The following business questions were answered using SQL:

- Revenue by Gender
- High Spending Discount Users
- Top 5 Highest Rated Products
- Shipping Type Comparison
- Subscribers vs Non-Subscribers Analysis
- Discount Dependent Products
- Customer Segmentation
- Top 3 Products in Each Category
- Repeat Buyers vs Subscription Status
- Revenue by Age Group

---

## 📈 Power BI Dashboard

The dashboard provides interactive insights including:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Status Analysis
- Interactive Filters

---

## 💡 Key Business Insights

- Male customers generated higher revenue than female customers.
- Express shipping users spent slightly more on average.
- Loyal customers represented the largest customer segment.
- Some products relied heavily on discounts for sales.
- Young adults contributed the highest revenue.
- Top-rated products should be prioritized in marketing campaigns.

---

## 📌 Business Recommendations

- Increase subscription benefits to improve customer retention.
- Launch loyalty programs for repeat customers.
- Optimize discount strategies to protect profit margins.
- Promote top-rated and best-selling products.
- Focus marketing campaigns on high-revenue customer segments.

---

## 📁 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── shopping_data.csv
│
├── Python/
│   ├── data_cleaning.ipynb
│   ├── feature_engineering.ipynb
│   └── database_upload.py
│
├── SQL/
│   └── business_queries.sql
│
├── Dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Customer Lifetime Value (CLV) Prediction
- Customer Churn Prediction
- Product Recommendation System
- Sales Forecasting
- Customer Segmentation using Machine Learning

---

## 👨‍💻 Author

**Om Wable**

- Data Science Enthusiast
- Python | SQL | PostgreSQL | Power BI | Machine Learning

---

## ⭐ If you found this project useful, don't forget to Star the repository!
