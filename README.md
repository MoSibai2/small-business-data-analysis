# Small Business Data Cleaning & Sales Analysis

A Python workflow that takes a messy small-business sales file, cleans it, and turns it into clear sales insights and charts.

## The Problem

Real business sales records are rarely clean. This simulated dataset contains the issues I see most often: duplicate rows, missing values, and invalid prices. The goal is to fix them transparently and then analyze sales performance.

## What I Did

1. **Inspected** structure, data types, missing values, duplicates, and invalid records.
2. **Cleaned** by removing duplicates, labeling missing categories as `Unknown`, excluding invalid prices, and separating records with missing quantities.
3. **Prepared** the data by converting order dates to datetime and calculating total revenue.
4. **Analyzed** sales by product, category, city, payment method, and month.
5. **Visualized** key findings with charts.
6. **Recommended** practical next steps for the business.

## Data Cleaning Summary

| Step | Result |
|---|---|
| Original rows | 13 |
| Duplicate rows removed | 1 |
| Negative unit price (excluded) | 1 |
| Missing quantity (separated) | 1 |
| Final valid records | 10 |

## Key Metrics

| Metric | Result |
|---|---|
| Total Revenue | 62,050 EGP |
| Total Orders | 10 |
| Total Items Sold | 13 |
| Average Order Value | 6,205 EGP |

## Charts

![Revenue by product](images/revenue_by_product.png)
![Revenue by city](images/revenue_by_city.png)
![Revenue by payment method](images/revenue_by_payment.png)

## Key Insights

- **Laptop** was the top revenue product: 45,000 EGP (72.5% of revenue).
- **Electronics** generated 57,000 EGP (91.9% of revenue).
- **Cairo** accounted for 51,000 EGP (82.2% of revenue).
- **Card payments** made up 83.48% of revenue.
- **Keyboard** had the highest quantity sold despite lower revenue than laptops and monitors.

## Business Recommendations

- Prioritize laptop inventory, since it drives most of the revenue.
- Explore accessory bundles and cross-selling with high-volume items like keyboards.
- Keep focusing on Cairo while testing growth in other cities.
- Improve data collection to reduce missing customer and payment information.
- Investigate invalid prices and incomplete orders before they reach business reports.

## Limitations

- The dataset is simulated and small (10 valid records, January 2026 only), so it demonstrates the **workflow**, not real trends.
- Findings do not represent an actual business.

## Skills Demonstrated

Data cleaning, data validation, exploratory data analysis, KPI calculation, data visualization, business reporting.

## How to Run

1. Open `small_business_data_analysis.ipynb` in Google Colab.
2. Run all cells from top to bottom.

## Project Structure

- `README.md`
- `small_business_data_analysis.ipynb`
- `images/` (charts used in this README)

## Author

**Mohamed Sibai (MoSibai)**
GitHub: [MoSibai2](https://github.com/MoSibai2)
