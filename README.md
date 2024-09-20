# Superstore Sales Analysis
This project provides a detailed analysis of sales data from a Superstore. The analysis covers sales trends, customer behavior, product performance, and regional insights. Various visualizations and metrics are used to highlight patterns and trends that can drive business decisions.

## Table of Contents

- Overview
- Key Insights
- Data
- Analysis
    - Average Sales per Product
    - Most and Least Sold Products
    - Sales Distribution by Region
    - Top 5 Best-Selling Products
    - Monthly and Yearly Sales
    - Discount vs. Sales Correlation
    - Sales Channels Performance
    - Weekday vs Weekend Orders
    - Sales Trends Over Time
    - Average Order Value by Product Category
    - Regional Sales Performance
    - Seasonal Sales Trends
    - Fulfillment Time Analysis
    - Customer Segmentation Analysis
- Visualizations
- Installation
- Repository Structure
- License
- Authors

## Overview
The Superstore Sales Analysis explores various aspects of sales, customer behavior, and product performance. The project uses Python libraries such as Pandas, Matplotlib, and Seaborn to provide insights through data visualizations.

## Key Insights
1. **Average Sales per Product:** Calculated the average sales for each product.
2. **Most/Least Sold Products:** Identified the most and least sold products based on sales data.
3. **Sales Distribution by Region:** Visualized sales across different regions.
4. **Top 5 Best-Selling Products:** Highlighted the top 5 products by sales.
5. **Monthly/Yearly Sales:** Analyzed sales trends over time.
6. **Correlation Between Discount and Sales:** Analyzed the relationship between discounts and sales.
7. **Sales Channels Performance:** Compared sales across different delivery modes (e.g., Standard, Same Day).
8. **Weekday vs. Weekend Orders:** Analyzed order patterns between weekdays and weekends.
9. **Sales Trends Over Time:** Examined the overall trend in sales over months and years.
10. **Product Category Performance:** Identified product categories with the highest and lowest average order values.
11. **Regional Sales Performance:** Analyzed the sales performance across different regions.
12. **Seasonal Sales Trends:** Explored sales trends during different seasons (spring, summer, autumn, winter).
13. **Fulfillment Time:** Calculated the average fulfillment time for orders.
14. **Customer Segments:** Analyzed which customer segments (e.g., Consumer, Corporate, Home Office) spent the most.


## Data

The dataset contains 9,994 entries with columns such as:

- `Order Date`: The date when the order was placed.
- `Ship Date`: The date when the order was shipped.
- `Sales`: The total sales amount for the order.
- `Region`: The region where the sale was made.
- `Product Category`: The category of the product sold.
- `Discount`: The discount applied to the sale.
- `Profit`: The profit generated from the sale.

## Analysis
### 1. Average Sales per Product
Calculated the average sales for each product by grouping the sales data.

### 2. Most and Least Sold Products
Identified the most sold product (e.g., Cisco TelePresence System EX90) and the least sold product (e.g., Hoover Replacement Belt).

### 3. Sales Distribution by Region
Visualized the total sales across regions, identifying which regions performed the best.

### 4. Top 5 Best-Selling Products
Highlighted the top 5 best-selling products based on sales data.

### 5. Monthly and Yearly Sales
Analyzed the sales trends month by month and year by year.

### 6. Correlation Between Discount and Sales
Identified a slight negative correlation (-0.028) between discount and sales.

### 7. Sales Channels Performance
Analyzed sales based on delivery modes, identifying that Standard Class has the highest sales.

### 8. Weekday vs Weekend Orders
Found that the majority of orders were placed on weekdays, with a significant difference from weekends.

### 9. Sales Trends Over Time
Analyzed the sales trends over time and identified seasonal patterns.

### 10. Product Category Performance
Technology had the highest average order value, while Office Supplies had the lowest.

### 11. Regional Sales Performance
The West region had the highest sales, while the South region had the lowest.

### 12. Seasonal Sales Trends
Autumn had the highest sales, followed by Spring, Winter, and Summer.

### 13. Fulfillment Time
The average fulfillment time was approximately 3.96 days.

### 14. Customer Segments
The Consumer segment had the highest sales, followed by Corporate and Home Office segments.

## Visualizations
Below are some key visualizations from the analysis.

**Sales Distribution by Region**

**Monthly Sales Trend**

**Average Sales per Product Category**

**Sales Channels Performance**


## Installation
To run this analysis on your local machine, follow these steps:

1. **Clone the repository:**
git clone https://github.com/Haroon1056/Student-Result-Data-Analysis.git

2. **Run the Jupyter notebook:**
Jupyter notebook

## Repository Structure

superstore-sales-analysis/
│
├── data/
│   └── superstore_sales_data.csv        # The dataset
│
├── images/
│   └── sales_distribution_region.png    # Sales distribution by region
│   └── monthly_sales_trend.png          # Monthly sales trend
│   └── sales_per_category.png           # Average sales by product category
│   └── sales_channels.png               # Sales performance by channel
│
├── notebooks/
│   └── superstore_sales_analysis.ipynb  # Jupyter Notebook with analysis
│
├── README.md

## License
This project is licensed under the MIT License.


## Authors

- [@HaroonRasheed](https://github.com/Haroon1056)

