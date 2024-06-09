# Elasticity Analysis and Revenue Optimization Project
This project aims to analyze the price elasticity of products in the "laptop, computer" category sold by Bestbuy.com, and optimize the pricing strategy to maximize revenue. Through exploratory data analysis (EDA) and statistical modeling, we identify products with significant price elasticity and simulate the impact of price changes on revenue.

## About the Project
The dataset contains various attributes such as product name, category, price, discount price, merchant, brand, and sales data. The goal is to identify the price sensitivity of products and use this information to recommend pricing adjustments that can enhance revenue.

## Insights Obtained
During the exploratory data analysis (EDA), several valuable insights were obtained:

1. **Most Sold Categories:** Identified the top-selling product categories.
2. **Most Sold Brands:** Determined the brands with the highest sales volume.
3. **Sales Patterns:** Analyzed sales trends by day of the week, month, and week number.
4. **Price Elasticity:** Estimated the price elasticity of various products to understand how price changes impact demand.

## Code Structure
### 1. Imports
We imported the necessary libraries for data analysis, visualization, and modeling.

### 2. Dataset Loading
We loaded the dataset and performed initial cleaning, removing unnecessary columns.

### 3. Data Description
We renamed the columns for easier interpretation and checked dimensions, data types, and missing values.

### 2.0 EDA
We kickstart by creating a copy of the original dataset for analysis purposes.

### 2.2 What is the most sold category?
The analysis reveals the top-selling categories.

### 2.2.1 Most Sold Categories by Store
We identify the top-selling categories for each store.

### 2.3 What is the most sold brand?
The investigation focuses on determining the brands with the highest sales volume.

### 2.3.1 Most Sold Brands by Store
We identify the top-selling brands for each store.

### 2.4 What are the best selling days?
Sales trends are scrutinized by day of the week.

### 2.4.1 Best Selling Days by Store
We pinpoint the days with the highest sales for each store.

### 2.5 What are the best selling months?
Sales trends are examined by month.

### 2.5.1 Best Selling Months by Store
We identify the months with the highest sales for each store.

### 2.6 What are the best selling weeks?
Sales trends are explored by week number.

### 2.6.1 Best Selling Weeks by Store
We highlight the weeks with the highest sales for each store.

### 5. Feature Engineering
We created new features from existing data to enrich the analysis:

Defining Elasticity Dataset: Selected a subset of data focusing on laptops from Bestbuy.com.
Calculating Average Prices and Demand: Grouped data by product name and week number to calculate average prices and demand.

### 6. Machine Learning
We used statistical models to estimate price elasticity. Products with significant elasticity were selected for further analysis.

Elasticity Estimation: Calculated the price elasticity for each product and selected those with p-value < 0.05.

### 7. Business Performance
We simulated the impact of price changes on revenue based on the estimated price elasticity of selected products.

**Revenue Simulation:** Estimated the new revenue, revenue variation, and percentage variation after a 10% price reduction.

### Conclusion

This project provides a solid foundation for analyzing price elasticity and optimizing pricing strategies. By understanding the price sensitivity of different products, Bestbuy.com can adjust prices to maximize revenue, enhancing overall business performance. The insights obtained from this analysis enable more informed decision-making and strategic planning.
