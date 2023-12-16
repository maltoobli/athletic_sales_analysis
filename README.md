# Sales Data Analysis

This repository contains Python code for analyzing sales data. The code utilizes Pandas for data manipulation and analysis. The following steps were performed:

## 1. Data Cleaning and Combination

- Imported two CSV files: `athletic_sales_2020.csv` and `athletic_sales_2021.csv`.
- Checked and adjusted data types in both datasets.
- Combined sales data from 2020 and 2021 into a single DataFrame.
- Handled null values and converted the "invoice_date" column to datetime format.

## 2. Regional Product Analysis

- Determined the regions, states, and cities that sold the most products.
- Utilized both `groupby` and `pivot_table` methods to showcase the top 5 regions by total products sold.

## 3. Regional Sales Analysis

- Explored the total sales for products sold in different regions, states, and cities.
- Applied `groupby` and `pivot_table` methods to highlight the top 5 regions by total sales.

## 4. Retailer Sales Analysis

- Investigated total sales by retailer across various regions, states, and cities.
- Utilized `groupby` and `pivot_table` methods to identify the top 5 retailers by total sales.

## 5. Women's Athletic Footwear Analysis

- Filtered data to focus on sales of "Women's Athletic Footwear."
- Analyzed sales by retailers, regions, states, and cities for this product.
- Determined the top 5 retailers by the total number of women's athletic footwear sold.

## 6. Time-based Analysis

- Explored the day and week with the most sales for women's athletic footwear.
- Resampled data to observe daily and weekly sales trends.

### Note

This analysis provides insights into regional, retailer, and product-based sales trends for athletic products, with a specific focus on women's athletic footwear.

For more details, refer to the respective Python code files in this repository.

Sales Product Data. Available: https://www.kaggle.com/datasets/knightbearr/sales-product-data