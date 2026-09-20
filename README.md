## Project File
- `bi_report.pbix`
  <img width="2170" height="1130" alt="image" src="https://github.com/user-attachments/assets/09f84280-7b15-489b-b41b-44b191c56b8d" />


## Objectives
- Analyze monthly order trends
- Compare orders with the previous year
- Analyze revenue trends
- Calculate YoY variation
- Analyze customer rating distribution
- Analyze performance by state and product category

## Tools
- Power BI Desktop
- Power Query
- DAX

## Data Model
The report uses a star schema with:
- FactSales
- DimCustomer
- DimProduct
- DimDate

## Files Used

The analysis was built using the following Olist datasets:

- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_products_dataset.csv`
- `olist_order_reviews_dataset.csv`
- `olist_customers_dataset.csv`

## Main KPIs
- Order Count
- Order Count PY
- Order YoY %
- Total Revenue
- Revenue PY
- Revenue YoY %
- Average Rating

## Report Pages
- Orders
- Revenue
- Ratings
