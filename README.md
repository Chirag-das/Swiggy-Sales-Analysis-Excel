# Swiggy Sales & Performance Dashboard

## Project Overview

An interactive **Excel dashboard** built to analyze Swiggy food-order data and identify sales, order, restaurant, geographic, food-type, and rating trends.

The project converts raw transactional data into a management-friendly dashboard using **Microsoft Excel, PivotTables, PivotCharts, slicers, formulas, and a geographic map**.

## Business Questions

- What are the total sales and total orders?
- What is the average order value?
- How do sales change month by month?
- Which days of the week generate the most sales?
- Which states and cities contribute the most sales?
- Which restaurant brands generate the highest sales?
- How does sales performance differ between Veg and Non-Veg orders?
- How does sales performance vary by quarter?
- What is the overall average rating?

## Key KPIs

| KPI | Result |
|---|---:|
| Total Sales | ₹5.30 Cr |
| Total Orders | 197,430 |
| Average Order Value | ₹268.51 |
| Average Rating | 4.34 |
| Rating Count* | 55,91,574 |

\* Rating Count is the sum of the `Rating Count` field provided in the source dataset; it should not automatically be interpreted as unique customers or unique reviews.

## Dashboard Features

- KPI cards
- Monthly sales trend
- Sales by day of week
- Sales by state using an India map
- Top 10 restaurants by sales
- Top 5 cities by sales
- Sales by food type
- Quarter-wise sales, orders and average rating
- Interactive slicers for Month, Food Type, and State

## Key Business Insights

1. **Total sales reached ₹5.30 Cr across 197,430 records/orders**, with an average order value of ₹268.51.
2. **Bengaluru is the leading city**, generating approximately ₹54.57 lakh and accounting for about 10.3% of total sales.
3. **Karnataka is the top-performing state**, also contributing approximately ₹54.57 lakh.
4. **Veg sales dominate**, contributing ₹3.38 Cr, or about 63.8% of total sales.
5. **Saturday is the strongest sales day**, with approximately ₹77.83 lakh in sales. Tuesday is the lowest at approximately ₹73.59 lakh.
6. **May is the highest-sales month** at approximately ₹67.94 lakh, while February is the lowest at approximately ₹62.69 lakh.
7. **KFC is the highest-selling restaurant brand** in the dataset at approximately ₹42.47 lakh.
8. **Q2 slightly outperformed Q1**, with ₹1.99 Cr versus ₹1.97 Cr in sales. Q3 is only a partial quarter because the dataset covers January through August.
9. The **top five cities contribute about 32.9% of total sales**, showing meaningful concentration among major markets.
10. The **top ten restaurant brands contribute about 34.2% of total sales**, indicating that a relatively small group of brands drives a substantial share of sales.

## Tools & Techniques

- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Excel formulas
- Conditional formatting
- Geographic map visualization
- Data aggregation and KPI analysis

## Dataset

The workbook contains 197,430 rows and 14 fields, including:

`State`, `City`, `Order Date`, `Month`, `Day`, `Quarter`, `Restaurant Name`, `Location`, `Category`, `Dish Name`, `Food Type`, `Price (INR)`, `Rating`, and `Rating Count`.

**Data period:** January–August 2025.

## Repository Structure

```text
Swiggy-Sales-Analysis/
│
├── README.md
├── BUSINESS_INSIGHTS.md
├── DATA_DICTIONARY.md
├── Swiggy Sales Data.xlsx
└── Final Dashboard.png
```

## Dashboard Preview
<img width="2113" height="1223" alt="Final Dashboard" src="https://github.com/user-attachments/assets/98f87412-3871-4d4e-81c1-d1a567773f0d" />




## Conclusion

The analysis highlights strong sales concentration in major cities and restaurant brands, a clear preference toward Veg sales, and noticeable variation in sales across months and days of the week. The dashboard provides an interactive way to explore these patterns and support data-driven business decisions.

