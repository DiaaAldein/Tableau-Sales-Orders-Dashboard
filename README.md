# Sales Orders Dashboard — Tableau

**Author:** Diaa Aldein Alsayed Ibrahim Osman | [LinkedIn](http://www.linkedin.com/in/diaa-ibrahim-31381656)
**Program:** Epsilon AI Institute — CDAP Diploma project

## Overview
Interactive dashboard over **60,000+ sales-order records and 18,000+ customers**, built on a Tableau relationship data model: the fact table related to Customer, Product, Sales Territory, and Currency dimensions.

## Dashboard

![Tableau Dashboard](Tableau%20Dashboard.png)

## Views
1. **Geographical Decomposition** — map of order volume by country (color-encoded measure)
2. **Time Series** — monthly order trend on Order Date, using a calculated field `Number of Order = COUNT([PK])`
3. **Product Behavior** — top 10 products ranked by order count, with a product-name filter

All three unified in a single cross-filtering dashboard, with a date-range slider and product filter applied globally.

## Files
- `Book1.twbx` — packaged Tableau workbook (open in Tableau Desktop or Tableau Public)
- `Epsilon - New - Order Data.xlsx` — source data (60,402 orders / 18,484 customers)
- `Tableau Dashboard.png` — dashboard screenshot
