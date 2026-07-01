# Bike Store Sales Dashboard 🚲📊

## Overview
This repository contains a data analysis and visualization project focused on bicycle store sales performance. The project features an interactive dashboard designed to track key sales metrics, identify top-performing stores and products, and analyze revenue trends over a specific time period.

## Dataset
The analysis is based on the `store_sales.csv` dataset, which includes 1,000 transaction records. The dataset consists of the following key columns:
- `store_name`: The name of the store (e.g., Baldwin Bikes, Santa Cruz Bikes, Rowlett Bikes).
- `product_name`: The specific bicycle model, parts, or frameset sold.
- `order_date`: The date the transaction took place (data spans from 2016 to 2018).
- `total_quantity`: The number of units sold per transaction.
- `total_price`: The total revenue generated from the transaction.

## Dashboard Features
The interactive dashboard provides comprehensive insights through three primary visualizations:
1. **Top Store by Price and Quantity (Pie Chart):** Illustrates the overall market share and sales contribution of each store. For instance, Baldwin Bikes dominates the sales volume with a 71.80% share.
2. **Top 10 Products by Quantity (Bar Chart):** Ranks the best-selling bicycle models based on the total number of units sold, providing clear insights into customer preferences and inventory demand.
3. **Price by Year and Month (Line Chart):** A time-series analysis displaying revenue trends from January 2016 to September 2018. It highlights monthly sales fluctuations, including a significant revenue spike in early 2018.

### Interactive Controls
- **Order Date Slider:** Allows users to adjust and filter the analysis timeframe interactively.
- **Store Name Filter:** Checkboxes that enable users to isolate data for specific stores or view the aggregated performance of all stores.

## Tools Used
* **Data Source:** CSV File (`store_sales.csv`)
* **Data Visualization:** [Insert your visualization tool here, e.g., Tableau / Power BI]
* **Data Processing:** [Insert if you used any, e.g., Python (Pandas), SQL, or Excel]

## Repository Structure
- `store_sales.csv`: The raw dataset used for building the dashboard.
- `dashboard.png`: Screenshots of the final interactive dashboard.
