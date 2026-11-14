# Small Business Data Cleaning & Sales Analysis

## Project Overview

This project demonstrates a practical data cleaning and exploratory data analysis workflow for a small business sales dataset using Python, Pandas, and Matplotlib.

The dataset is simulated and contains common data quality issues that may appear in real-world business records, including duplicate rows, missing values, and invalid prices.

The goal is to clean the data, analyze sales performance, visualize key metrics, and generate actionable business insights.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab

## Project Workflow

1. **Data Inspection:** Examined dataset structure, data types, missing values, duplicates, and invalid records.
2. **Data Cleaning:** Removed duplicate rows, handled missing categorical values, identified invalid prices, and separated records with missing quantities.
3. **Data Preparation:** Converted order dates into datetime format and calculated total revenue.
4. **Exploratory Data Analysis:** Analyzed sales performance by product, category, city, payment method, and month.
5. **Data Visualization:** Created charts to communicate important findings.
6. **Business Insights:** Summarized findings and provided practical recommendations.

## Key Business Metrics

| Metric | Result |
|---|---:|
| Total Revenue | 62,050 EGP |
| Total Orders | 10 |
| Total Items Sold | 13 |
| Average Order Value | 6,205 EGP |

## Key Insights

- **Laptop** was the top revenue-generating product, contributing 45,000 EGP (72.5% of total revenue).
- **Electronics** generated 57,000 EGP, representing 91.9% of total revenue.
- **Cairo** accounted for 51,000 EGP (82.2% of total revenue).
- **Card payments** represented 83.48% of total revenue.
- **Keyboard** had the highest quantity sold, despite generating less revenue than laptops and monitors.

## Business Recommendations

- Prioritize laptop inventory management due to its significant contribution to revenue.
- Explore accessory bundles and cross-selling opportunities.
- Focus on the Cairo market while exploring growth opportunities in other cities.
- Improve data collection to reduce missing customer and payment information.
- Investigate invalid prices and incomplete order records before including them in business reports.

## Data Quality & Limitations

- The original dataset contained 13 rows, including one duplicate.
- One record with a negative unit price was excluded from the analysis.
- One record with a missing quantity was separated and excluded from revenue calculations.
- Missing city and payment method values were labeled as `Unknown`.
- The final analysis included 10 valid records.
- The dataset covers January 2026 only and is too small to establish reliable long-term trends.
- All data is simulated; findings do not represent an actual business.

## How to Run

1. Open the notebook in this repository.
2. Open it using Google Colab.
3. Run all cells from top to bottom.

## Project Structure

```text
small-business-data-analysis/
│
├── README.md
└── small-business-data-analysis.ipynb
```

## Author

**MoSibai**

GitHub: [MoSibai2](https://github.com/MoSibai2)
