# 🛒 Customer Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.12-blue)
![SQL](https://img.shields.io/badge/PostgreSQL-SQL-green)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional retail data containing **3,900 customer purchases across 18 attributes**.

The objective is to uncover customer spending patterns, product preferences, loyalty trends, and purchasing behavior to support data-driven business decisions.

The project combines:

- Python for Data Cleaning & Transformation
- PostgreSQL for Business Analytics
- Power BI for Dashboard Development
- GitHub for Version Control

---

## 🎯 Business Problem

A leading retail company wants to understand customer shopping behavior and identify the factors influencing purchasing decisions.

### Business Questions

- Which customer segments generate the highest revenue?
- How do discounts impact purchasing behavior?
- Which products receive the highest ratings?
- Are subscription members more valuable customers?
- Which age groups contribute most to revenue?
- How can customer loyalty be improved?

---

## 📊 Dataset Summary

| Metric | Value |
|----------|----------|
| Rows | 3,900 |
| Columns | 18 |
| Missing Values | 37 |
| Categories | Clothing, Accessories, Footwear, Outerwear |
| Customer Attributes | Age, Gender, Location, Subscription Status |
| Purchase Attributes | Product, Season, Discount, Purchase Amount |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|--------|----------|
| Python | Data Cleaning |
| Pandas | Data Manipulation |
| PostgreSQL | Data Analysis |
| SQL | Business Queries |
| Power BI | Dashboard Creation |
| GitHub | Project Management |

---

# 🔄 Project Workflow

## 1️⃣ Data Cleaning & Preparation (Python)

- Loaded dataset using Pandas
- Handled missing values in Review Rating
- Standardized column names
- Created customer age groups
- Removed redundant columns
- Exported clean dataset to PostgreSQL

---

## 2️⃣ SQL Business Analysis

### Revenue Analysis

- Revenue by Gender
- Revenue by Age Group

### Customer Analysis

- Customer Segmentation
- Repeat Buyers Analysis
- Subscription Behavior

### Product Analysis

- Top Rated Products
- Top Products per Category
- Discount Dependent Products

### Purchase Behavior

- High Spending Discount Users
- Shipping Type Comparison
- Subscriber vs Non-Subscriber Analysis

---

# 📈 Key Insights

## Revenue by Gender

| Gender | Revenue |
|----------|----------|
| Male | $157,890 |
| Female | $75,191 |

---

## Top Rated Products

| Product | Rating |
|----------|----------|
| Gloves | 3.86 |
| Sandals | 3.84 |
| Boots | 3.82 |
| Hat | 3.80 |
| Skirt | 3.78 |

---

## Customer Segmentation

| Segment | Customers |
|----------|----------|
| Loyal | 3,116 |
| Returning | 701 |
| New | 83 |

---

## Revenue by Age Group

| Age Group | Revenue |
|-----------|-----------|
| Young Adult | $62,143 |
| Middle-aged | $59,197 |
| Adult | $55,978 |
| Senior | $55,763 |

---

# 📊 Power BI Dashboard

## Dashboard Preview

### Overview Dashboard

<img width="1543" height="865" alt="image" src="https://github.com/user-attachments/assets/82901976-a92b-406a-8b9b-4628ce2fa40a" />

---

## Dashboard Features

✅ Customer Overview

✅ Revenue Analysis

✅ Category Performance

✅ Age Group Insights

✅ Subscription Analysis

✅ Sales Distribution

---

# 💡 Business Recommendations

### Increase Subscription Adoption

Provide exclusive benefits and personalized offers to subscribers.

### Strengthen Loyalty Programs

Reward repeat customers to maintain customer retention.

### Optimize Discount Strategy

Monitor discount-heavy products to maintain profitability.

### Improve Product Marketing

Promote top-rated products through targeted campaigns.

### Focus on High Revenue Age Groups

Young Adults contribute the highest revenue and should be targeted with personalized marketing.

---


# 🚀 How To Run

## Clone Repository

```bash
git clone https://github.com/tech-vijay/Customer-Shopping-Analysis.git
```

## Install Dependencies

```bash
pip install pandas numpy psycopg2
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 👨‍💻 Author

### Vijay Maurya

B.Tech CSE (AI & ML)

Lamrin Tech Skills University

### Connect With Me

- GitHub: https://github.com/tech-vijay
- LinkedIn: https://www.linkedin.com/in/vijaymaurya563/

---

⭐ If you found this project useful, consider giving it a Star.
