# Retail Sales Analytics Report

## Executive Summary

This project analyzes a retail sales dataset containing 100 customers, 50 products, and 500 orders. The dataset shows strong revenue concentration in a few customers, products, and cities, with the Sports category leading overall sales. The analysis below is based on the CSV data in the Dataset folder.

## Dataset Snapshot

| Metric | Value |
| --- | ---: |
| Customers | 100 |
| Products | 50 |
| Orders | 500 |
| Unique Cities | 10 |
| Unique Categories | 5 |
| Total Quantity Sold | 1,542 |
| Total Revenue | 40,666,206.67 |
| Average Order Value | 81,332.41 |
| Average Items Per Order | 3.08 |

### Customer Distribution

| Metric | Value |
| --- | ---: |
| Male Customers | 57 |
| Female Customers | 43 |

The largest customer bases are in Warangal, Kolkata, Mumbai, and Vijayawada.

| City | Customers |
| --- | ---: |
| Warangal | 19 |
| Kolkata | 14 |
| Mumbai | 12 |
| Vijayawada | 12 |
| Pune | 9 |

### Top Customers by Revenue

| Customer | Revenue | Orders |
| --- | ---: | ---: |
| Pooja Sharma | 1,564,151.52 | 12 |
| Kiran Verma | 1,481,634.93 | 19 |
| Aditya Yadav | 1,441,344.21 | 17 |
| Kavya Verma | 1,140,170.43 | 15 |
| Sneha Sharma | 1,136,377.69 | 16 |

### Customer Activity Pattern

- The most active customer by order count is Kiran Verma with 19 orders.
- 59 customers placed 5 or more orders.
- Only 4 customers placed 10 or more orders.
- This indicates that repeat purchasing exists, but high-frequency buying is concentrated in a small group.

### Category Distribution

All five categories are evenly represented in the product master data, with 10 products in each category.

| Category | Products |
| --- | ---: |
| Electronics | 10 |
| Clothing | 10 |
| Home | 10 |
| Groceries | 10 |
| Sports | 10 |

### Category Revenue

| Category | Revenue |
| --- | ---: |
| Sports | 11,252,619.28 |
| Home | 9,335,932.52 |
| Clothing | 7,582,847.13 |
| Groceries | 7,250,858.65 |
| Electronics | 5,243,949.09 |

Sports is the highest-performing category by a clear margin, while Electronics contributes the least revenue among the five categories.

### Top Products by Revenue

| Product | Category | Revenue | Quantity Sold |
| --- | --- | ---: | ---: |
| Football | Sports | 2,019,017.50 | 50 |
| Cycling Bottle | Sports | 1,825,563.96 | 44 |
| Juice | Groceries | 1,564,512.81 | 37 |
| Fan | Home | 1,515,399.06 | 42 |
| Yoga Mat | Sports | 1,510,626.28 | 31 |

### Price Summary

| Metric | Value |
| --- | ---: |
| Lowest Product Price | 1,410.07 |
| Highest Product Price | 48,729.88 |
| Average Product Price | 26,398.82 |

The highest-value products drive a significant share of revenue, which suggests that price-sensitive and premium products both play important roles in the mix.

### Order Date Range

- First order date: 2025-01-06
- Last order date: 2026-06-25

### Monthly Revenue Peaks

| Month | Revenue |
| --- | ---: |
| 2026-05 | 3,625,180.32 |
| 2026-01 | 2,964,160.80 |
| 2025-11 | 2,807,653.08 |
| 2025-03 | 2,806,852.07 |
| 2026-04 | 2,714,225.58 |

### Lowest Revenue Months

| Month | Revenue |
| --- | ---: |
| 2025-01 | 697,293.11 |
| 2025-09 | 1,127,768.46 |
| 2026-06 | 1,459,519.22 |
| 2025-06 | 1,732,142.58 |
| 2025-08 | 1,787,045.55 |

Revenue is uneven across the calendar, with a strong surge in early 2026 and a particularly strong month in May 2026.

### Revenue by City

| City | Revenue |
| --- | ---: |
| Warangal | 8,010,298.32 |
| Mumbai | 6,292,788.97 |
| Kolkata | 5,076,205.55 |
| Vijayawada | 5,006,584.64 |
| Chennai | 3,578,610.37 |

Warangal leads both in customer count and revenue contribution, making it the strongest market in this dataset.

### Order Volume

- Minimum orders per customer: 1
- Maximum orders per customer: 13
- Average orders per customer: 5.0

### Most Frequent Products by Order Count

| Product | Orders |
| --- | ---: |
| Table | 17 |
| Football | 16 |
| Cycling Bottle | 15 |
| Track Pants | 14 |
| Mouse | 14 |

The most frequently ordered products are not always the highest revenue products. This indicates a mix of high-volume, lower-priced items and lower-volume, higher-priced items.

## Key Findings

- Sports is the top revenue-generating category.
- Warangal is the strongest city by both customer presence and sales value.
- A small set of customers contributes a disproportionate share of total revenue.
- Revenue is concentrated in a handful of products, especially within Sports.
- Sales performance varies noticeably by month, with the best results clustered in early 2026.

## Data Limitations

The SQL scripts in this project include procedures and views that reference fields such as PaymentMethod and OrderStatus. Those columns are not present in the current CSV dataset, so analytics for payment-method revenue, status-based order counts, and cancelled-order loss cannot be computed from the available data.

## Conclusion

The dataset represents a healthy retail sales workload with clear concentration in certain cities, customers, and high-performing product categories. The most actionable opportunities are likely in expanding the Sports category, retaining top customers, and studying the seasonal spikes that appear in the later months of the dataset.