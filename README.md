# Mobile Sales Analysis Dashboard

## Executive Summary

### 1. Project Overview

The Mobile Sales Analysis Dashboard provides a consolidated view of mobile phone sales performance across brands, mobile models, geographic locations, payment methods, and customer ratings. Developed using Microsoft Power BI, the dashboard transforms transaction-level data into actionable business insights to support sales monitoring and decision-making.

The analysis uses an Excel dataset containing **3,835 transactions**, **19,150 mobile units sold**, five brands, 15 mobile models, and 19 cities.

### 2. Key Performance Indicators

| KPI | Result |
|---|---:|
| Total sales revenue | ₹769.20 million (₹76.92 crore) |
| Units sold | 19,150 |
| Unique transactions | 3,835 |
| Average price per unit | Approximately ₹40,114 |
| Brands represented | 5 |
| Mobile models represented | 15 |
| Cities represented | 19 |

These KPIs provide an overview of revenue generation, sales volume, transaction activity, and product pricing.

### 3. Key Business Findings

#### Brand Performance

Apple leads the five brands with approximately **₹161.62 million** in sales, contributing about **21.01%** of total revenue. Samsung follows with approximately **₹160.04 million**. Together, Apple and Samsung account for approximately **41.82%** of total sales. Xiaomi records the lowest revenue among the five brands.

#### Geographic Performance

Delhi is the leading sales market, generating approximately **₹203.88 million**, followed by Mumbai at **₹127.19 million**. Together, these two cities contribute approximately **43.05%** of total revenue, indicating that sales are concentrated in these markets.

#### Monthly Sales Quantity

July records the highest aggregated monthly quantity at **1,700 units**, while February records the lowest at **1,451 units**. These figures combine the same calendar month across the dataset's available years and should be investigated further before drawing conclusions about seasonality.

#### Payment Preferences

UPI is the most frequently used payment method, accounting for **26.36%** of transactions. Debit cards, credit cards, and cash each account for approximately one-quarter of transactions. This indicates that customers use a relatively balanced mix of payment methods.

#### Customer Satisfaction

The average customer rating is approximately **3.69 out of 5**. Ratings of 4 or 5 account for **60.78%** of transactions, while ratings of 1 or 2 account for **22.22%**. This suggests an opportunity to investigate the causes of lower customer ratings and identify ways to improve the customer experience.

#### Mobile Model Performance

iPhone SE is the highest-revenue model, generating approximately **₹59.57 million**, followed by OnePlus Nord at **₹57.89 million** and Galaxy Note 20 at **₹56.01 million**. These models are strong candidates for further analysis of demand, pricing, and profitability.

### 4. Business Recommendations

1. **Strengthen market analysis:** Investigate the factors contributing to the strong sales performance of Delhi and Mumbai and evaluate opportunities in other cities.
2. **Optimize product strategy:** Compare brand and model performance using revenue, quantity sold, average selling price, and profit margin before making inventory decisions.
3. **Improve customer satisfaction:** Investigate low customer ratings and analyze feedback, returns, and complaints where available.
4. **Maintain payment flexibility:** Continue supporting UPI, debit cards, credit cards, and cash, given the relatively balanced distribution of transactions.
5. **Analyze time-based performance:** Compare sales across individual months and years to identify genuine growth trends, seasonal patterns, and changes in demand.
6. **Monitor business performance:** Use interactive KPI cards, slicers, and charts to track sales and identify changes in product, regional, and payment performance.

### 5. Conclusion

The analysis shows that the mobile sales business generated approximately **₹76.92 crore** in recorded revenue across **3,835 transactions**. Apple and Samsung are the leading brands by revenue, Delhi is the largest market, UPI is the most frequently used payment method, and iPhone SE is the highest-revenue mobile model.

At the same time, customer ratings and geographic sales concentration provide areas for further investigation. A well-designed Power BI dashboard enables management to monitor these indicators, compare performance across business segments, and investigate opportunities for improvement.

The findings describe the recorded dataset and do not, by themselves, establish profitability, customer retention, or future sales growth. Additional cost, customer feedback, and historical performance data would strengthen future business decisions.

---

## Dashboard Components

The dashboard is designed to include:

- KPI cards for total sales, total quantity, total transactions, and average unit price
- Sales by city
- Monthly quantity trend
- Customer rating distribution
- Transactions by payment method
- Brand performance summary
- Sales by mobile model
- Sales by day of the week
- Interactive slicers for brand, mobile model, payment method, year, month, and city

## Tools and Technologies

- **Microsoft Power BI** — dashboard design and interactive visualizations
- **Microsoft Excel** — source data
- **Power Query** — data cleaning and transformation
- **DAX** — measures and calculations

## Notes and Limitations

- Revenue values are based on units sold multiplied by price per unit.
- Monthly quantity figures described above aggregate the same calendar month across the years in the dataset; they are not a continuous month-by-month time series.
- Sales revenue is not the same as profit. Cost and margin data are needed to assess profitability.
- Customer ratings show reported scores but do not explain the reasons behind satisfaction or dissatisfaction.
- Validate all figures against the final cleaned dataset and Power BI measures before publishing.
