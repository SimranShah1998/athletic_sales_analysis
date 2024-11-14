# Athletic Sales Analysis

## Description:

This project analyzes sales data for athletic products across the United States for the years 2020 and 2021. Using Python and pandas, the analysis aims to uncover key insights about regions, retailers, and sales trends for athletic wear, with a focus on women's athletic footwear.

The project walks through several steps, including combining and cleaning the data, performing groupby and pivot operations, and identifying high-performing categories and time periods.

## Objectives:

The main objectives of this analysis are:

1. Combine and clean the 2020 and 2021 sales data.

2. Identify the top-performing regions, states, and cities based on:

   - Number of products sold.

   - Total sales.
   
3. Determine the top retailers for athletic wear sales overall and for women's athletic footwear.

4. Analyze time-based trends to find the best-performing:

   - Days for women's athletic footwear sales.

   - Weeks for women's athletic footwear sales.

## Datasets

This analysis uses two datasets:

- athletic_sales_2020.csv: Contains sales data for the year 2020.

- athletic_sales_2021.csv: Contains sales data for the year 2021.

### Each dataset contains the following columns:

- retailer: Name of the retailer.

- retailer_id: Unique ID for the retailer.

- invoice_date: Date of the sale.

- region, state, city: Location of the sale.

- product: Name/category of the product sold.

- price_per_unit: Price of the product per unit.

- units_sold: Number of units sold.

- total_sales: Total sales amount for the transaction.

- operating_profit: Profit for the transaction.

- sales_method: Method of sale (e.g., In-store, Online).

## Steps Performed

1. Combine and Clean the Data

   - Combined the two datasets into a single DataFrame.

   - Dropped null values.

   - Converted the invoice_date column to a datetime format for time-based analysis.

2. Determine Which Region Sold the Most Products

   - Grouped data by region, state, and city to find the top-performing locations by the number of products sold.

3. Determine Which Region Had the Most Sales

   - Grouped data by region, state, and city to find the top-performing locations by total sales.

4. Determine Which Retailer Had the Most Sales

   - Analyzed total sales for each retailer across all regions, states, and cities.

5. Determine Which Retailer Sold the Most Women's Athletic Footwear

   - Filtered data for "Women's Athletic Footwear" products and identified the top retailers by sales.

6. Determine the Day with the Most Women's Athletic Footwear Sales

   - Resampled data by day to identify the top 10 days with the highest sales for women's athletic footwear.

7. Determine the Week with the Most Women's Athletic Footwear Sales

   - Resampled data by week to identify the top 10 weeks with the highest sales for women's athletic footwear.


## Results

### Key Insights:

- The top regions, states, and cities for product sales and total sales were identified.

- The best-performing retailers for overall athletic wear and women's athletic footwear were highlighted.

- Specific days and weeks with the highest sales for women's athletic footwear were determined, offering actionable insights for marketing and inventory strategies.

## Prerequisites

To run the analysis, you need:

- Python 3.7+

## The following Python libraries:

- pandas


## Conclusion:

The datasets were provided as part of an assignment to practice data analysis and visualization techniques
