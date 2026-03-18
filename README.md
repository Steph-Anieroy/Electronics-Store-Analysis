# Electronics Store Analysis

## Project Overview

This project focuses on analyzing sales performance by transforming raw sales data into a structured model and applying time intelligence calculations to evaluate trends in revenue, profit, and profitability across different business dimensions such as channel, product category, and geographical zone.

## Objective

*	Data Extraction, Transformation, and Loading (ETL)
    * Import the raw sales dataset.
    * Clean and transform the data to ensure consistency and usability.
    * Load the prepared dataset into the data model for analysis.
*	Date Table Creation and Data Modelling
    * Create a date table using DAX to enable time intelligence analysis.
    * Establish relationships between the date table and the sales dataset.
    * Design a structured data model to support accurate reporting.
*	Create Time Intelligence Measures (DAX)
    * Create the following measures in a dedicated Measure Table
    * Sales Year-To-Date (YTD)
    * Sales Quarter-To-Date (QTD)
    * Same Period Last Year (SPLY)
    * Sales Last Month
    * Sales Year-on-Year (YoY) Variance
    * Sales Year-on-Year (YoY) Variance %
    * Profit and Profit Margin %
    * Data Visualization and Reporting
    * Build interactive dashboard to analyze sales performance.
    * Visualize trends across multiple dimensions including;
      * Channel
      * Product Category
      * Zone
    * Display key performance indicators such as;
      * Revenue
      * Profit
      * Profit Margin
      * Year-on-Year sales performance


## Tools Used

* Powerpoint – for dashboard wireframing
*	PowerBI
*	Power Query Editor – For data transformation
*	Modelling
*	Table tool (Date table)
*	Measure table
*	DAX (PREVIOUSYEAR, SAMEPERIODLASTYEAR, CALCULATE, SUM, DIVIDE, TOTALQTD, TOTALYTD, SUMX, SWITCH, TRUE, FORMAT, UNICHAR etc.)
*	Visuals (Map, Clustered bar chart, Donut chart, line chart, Clustered column chart, and Tables)

## Data Description

*	Data contains 15,020 Rows and 13 Columns
*	Order ID
*	Order Date
*	Unit old
*	Price
*	Order Quantity
*	Sales
*	Channel
*	Promotion Name
*	Product Name
*	Product Category
*	Product Sub-category
*	State
*	Zone

## Key Analysis

*	Total Revenue
*	Total Profit
*	Unit Sold
*	Revenue YTD
*	Revenue QTD
*	Revenue YOY
*	Profit YOY
*	Revenue by Product Category
*	Revenue by Product 
*	Revenue by Zone
*	Revenue by State
*	Revenue by Channel
*	Yearly Revenue
*	Profit Trend
*	Yearly Profit
*	Product MOM
*	Quantity by Category
*	Quantity YOY

## Dashboard Preview
<img width="1233" height="690" alt="Electronic Data flook" src="https://github.com/user-attachments/assets/f6a8b29d-1bb2-486e-bbc7-a83365d225f5" />


<img width="1145" height="641" alt="Electronic store correct 2" src="https://github.com/user-attachments/assets/130e59b2-2749-4612-8439-5305241cb52d" />



## Key Insight

*	The electronics store generated $55.01M in revenue and $31.72M in profit, selling 246K units overall, indicating strong business performance.
*	Revenue and profit both increased by about 36% year over year, showing consistent business growth.
*	Computers are the top revenue generating category ($21M), followed by Cameras and Camcorders ($17M) and TV & Video ($9M).
*	Cell phones recorded the highest sales volume (92K units), meaning they sell more units even though computers generate more revenue.
*	Revenue steadily increased each year, with 2014 contributing the largest share of total sales.
*	Physical stores generate the majority of revenue ($31M), while online and reseller channels contribute smaller portions.
*	Southern regions, particularly South East and South South, produce the highest revenue, making them the strongest markets.
*	Profit trends generally increase throughout the year, peaking around October to November before dropping in December.
*	All product categories experienced positive year over year growth, with cell phones and audio products showing the fastest growth rates.
