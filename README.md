# E-Commerce Sales Analysis

An end-to-end sales analysis of 15,000 e-commerce orders (Jan 2023 – Dec 2024) using Excel and Power BI, covering data cleaning, KPIs, business insights and an interactive dashboard.

## Dataset Overview
- **Orders:** 15,000
- **Period:** 1 Jan 2023 – 31 Dec 2024
- **Coverage:** 7 states, 5 product categories, 25 products

## Tools Used
- Microsoft Excel (data cleaning, pivot tables, KPIs)
- Power BI (dashboard)

## 1. Data Cleaning
- **Duplicates:** No duplicate Order_IDs or fully duplicate rows (15,000 unique orders).
- **Missing values:** None found in any column.
- **Data types:** `Order_Date` set to date; `Quantity`, `Sales_Amount`, `Discount` and `Profit` set to numeric.
- **Text cleanup:** Trimmed extra spaces in category, product, state, city and payment mode.
- **Zero discount:** 246 rows have `Discount = 0`. These are valid "no discount" orders, so they were kept.

## 2. Key Performance Indicators

| KPI | Value |
|---|---|
| Total Sales | 49.4M (49,384,840) |
| Total Profit | 7.38M (7,377,771) |
| Total Orders | 15.0K (15,000) |
| Average Discount | 15.01% |
| Total Quantity Sold | 45.2K (45,191) |

## 3. Business Insights
- **Top state by sales:** Rajasthan (7.23M), followed by Karnataka and Gujarat (7.14M each).
- **Top category:** Electronics (10.23M sales), also the most profitable (1.55M profit).
- **Top products by sales:** Tablet (2.21M), Smartphone (2.15M), Skin Cream (2.09M).
- **Most used payment mode:** Cash on Delivery (3,059 orders, 20.4%).
- **Monthly trend:** Sales stay between about 1.7M and 2.2M. Lowest month is Feb 2023 (1.73M) and highest is Mar 2023 (2.24M).
- **Year over year:** 2023 (24.72M) and 2024 (24.66M) are almost equal.

## 4. Overall Observation
Sales and profit are spread evenly across states, categories, products and payment modes. The gap between top and bottom performers is only about 3–5%, so no single segment dominates. There is no clear rising or falling sales trend over the two years.

## 5. Project Files

| File | Description |
|---|---|
| `Cleaned_Ecommerce_Data.xlsx` | Cleaned dataset |
| `Ecommerce_Analysis_File.xlsx` | KPIs, pivot-style tables and insights |
| `Ecommerce_Sales_Dashboard.pbix` | Power BI dashboard |
| `Ecommerce_Sales_Dashboard.pdf` | Dashboard export (PDF) |

## Dashboard Preview
![Dashboard](dashboard_preview.png)

## Author
**Yogesh Sharma**

