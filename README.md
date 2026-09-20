## Project File
- `bi_report.pbix`

- ## Dashboard Preview

### Orders
<img width="2170" height="1130" alt="image" src="https://github.com/user-attachments/assets/09f84280-7b15-489b-b41b-44b191c56b8d" />
  ### Revenue
  <img width="2154" height="1134" alt="image" src="https://github.com/user-attachments/assets/ce63e6b4-f958-46b9-b303-8e843af3e4e3" />
  ### Ratings
<img width="2194" height="1130" alt="image" src="https://github.com/user-attachments/assets/827ee7e8-39c6-44d2-a564-c975079d475d" />


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
