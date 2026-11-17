# Brazilian E-Commerce Sales Analysis

An analysis of 96,000+ real e-commerce orders covering sales, product categories, payment methods, customer reviews, and delivery performance, using the Olist public dataset.

## Business Questions

- How is revenue distributed across product categories?
- How do customers prefer to pay?
- How satisfied are customers?
- How reliable is delivery?

## Dataset

[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
Orders, customers, sellers, products, payments, reviews, and delivery data from 2016 to 2018.

## Tools

Python, Pandas, NumPy, Matplotlib, Google Colab.

## Key Findings

| Metric | Result |
|---|---|
| Revenue (delivered orders) | 13.22 million BRL |
| Delivered orders analyzed | 96,478 |
| Average order value | 137.04 BRL |
| Top category by revenue | Health & Beauty |
| Top payment method by value | Credit Card (78.46%) |
| Average review score | 4.16 / 5 |
| On-time delivery rate | 91.89% |

## Charts

![Top categories by revenue](images/top_categories.png)
![Payment methods](images/payment_methods.png)
![Review scores](images/review_scores.png)
![Delivery performance](images/delivery_performance.png)

## Business Recommendations

- Invest in inventory and marketing for **Health & Beauty**, the top revenue category.
- Keep credit card (and installment) payments smooth, since they dominate payment value.
- Investigate the ~8% of late deliveries, because late orders are a likely source of low review scores.
- Track review scores per category and seller to find where satisfaction can improve.

## Limitations

- Only delivered orders are analyzed.
- Data covers 2016 to 2018 only.
- Revenue excludes shipping fees.
- The data cannot establish the exact causes of delivery delays or negative reviews.

## Skills Demonstrated

Data cleaning, merging multiple tables, exploratory data analysis, KPI calculation, data visualization, business insights.

## Project Structure

- `ecommerce_sales_analysis.ipynb`: main analysis notebook
- `images/`: charts used in this README
- `README.md`

## Author

**Mohamed Sibai (MoSibai)**
GitHub: [MoSibai2](https://github.com/MoSibai2)
