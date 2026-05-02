# 🛒 E-Commerce Sales Analysis

> **End-to-end data analysis project** — data generation, SQL querying, Python EDA, and an interactive Power BI–style dashboard.  
> Built by **Shinoy Babru** · [LinkedIn](https://www.linkedin.com/in/shinoy-babru-2000) · [GitHub](https://github.com/shinoybabru)  

---

## 📊 Project Overview

| Item | Detail |
|------|--------|
| **Dataset** | 1,000 synthetic e-commerce orders (2023) |
| **Categories** | Electronics · Clothing · Home & Kitchen · Books · Sports |
| **Tools** | Python · SQL (SQLite) · Power BI |
| **Key Metrics** | Revenue ₹2.86Cr · 1,000 Orders · 368 Customers |

---

## 🗂️ Project Structure

```
ecommerce-sales-analysis/
│
├── data/
│   ├── raw/
│   │   └── ecommerce_data.csv          # Raw generated dataset (1,000 rows)
│   └── processed/
│       └── cleaned_data.csv            # Cleaned & feature-engineered data
│
├── sql/
│   ├── 01_create_tables.sql            # Schema — 3 tables + indexes
│   ├── 02_load_data.sql                # Data loading instructions
│   └── 03_analysis_queries.sql         # 12 business intelligence queries
│
├── scripts/
│   ├── generate_data.py                # Synthetic dataset generator
│   ├── data_cleaning.py                # Cleaning & feature engineering
│   ├── analysis.py                     # EDA + chart export (8 PNG charts)
│   └── load_to_sqlite.py               # Loads data into SQLite database
│
├── notebooks/
│   └── ecommerce_analysis.ipynb        # Full Jupyter notebook walkthrough
│
├── outputs/                            # Exported charts (PNG)
│   ├── 01_monthly_revenue.png
│   ├── 02_revenue_by_category.png
│   ├── 03_top_products.png
│   ├── 04_order_status.png
│   ├── 05_revenue_by_state.png
│   ├── 06_payment_methods.png
│   ├── 07_quantity_vs_revenue.png
│   └── 08_orders_by_day.png
│
├── powerbi/
│   ├── ecommerce_dashboard.html        # Open in browser — no Power BI needed!
│   └── POWERBI_SETUP.md               # Step-by-step Power BI Desktop guide
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/shinoybabru/ecommerce-sales-analysis.git
cd ecommerce-sales-analysis
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Everything (in order)
```bash
python scripts/generate_data.py       # Generate raw dataset
python scripts/data_cleaning.py       # Clean & enrich data
python scripts/load_to_sqlite.py      # Load into SQLite DB
python scripts/analysis.py            # Run EDA & export 8 charts
```

### 4. Open the Jupyter Notebook
```bash
jupyter notebook notebooks/ecommerce_analysis.ipynb
```

### 5. View the Dashboard
Open `powerbi/ecommerce_dashboard.html` in any browser — fully interactive, no Power BI needed!

---

## 🔍 SQL Highlights

12 business queries in `sql/03_analysis_queries.sql`:

| # | Query | Business Question |
|---|-------|-------------------|
| 1 | KPI Summary | Overall revenue, orders, and AOV |
| 2 | Monthly Trend | Month-by-month revenue changes |
| 3 | Category Revenue | Which category earns the most? |
| 4 | Top 10 Products | Best-selling products by revenue |
| 5 | Revenue by State | Which states generate the most revenue? |
| 6 | Order Status | % of orders delivered vs cancelled |
| 7 | Payment Methods | How do customers prefer to pay? |
| 8 | Customer LTV | Top customers by lifetime spend |
| 9 | Shipping Speed | Average shipping days by status |
| 10 | Discount Impact | Do discounts drive larger orders? |
| 11 | Quarterly Revenue | Quarter-over-quarter comparison |
| 12 | Customer Segments | Repeat vs one-time buyers |

---

## 📈 Key Insights

- **Electronics** dominates — ₹2.04Cr revenue (71% of total)
- **Laptop** is the single highest-revenue product at ₹68.7L
- **63.4%** of orders are successfully delivered
- **Maharashtra** leads in regional revenue
- Average shipping time is **4 days**
- **Credit Card & UPI** are the most popular payment methods
- **March** is the peak revenue month

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Data generation, cleaning, EDA, visualisation |
| **Pandas & NumPy** | Data manipulation and analysis |
| **Matplotlib & Seaborn** | Chart creation and export |
| **SQL (SQLite)** | Structured querying and business analysis |
| **Power BI** | Interactive dashboard and reporting |
| **Jupyter Notebook** | Reproducible analysis walkthrough |

---

## 👤 Author

**Shinoy Babru**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shinoy%20Babru-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/shinoy-babru-2000)
[![GitHub](https://img.shields.io/badge/GitHub-shinoybabru-181717?style=flat&logo=github)](https://github.com/shinoybabru)

---
*Data Analyst · Python · SQL · Power BI*
