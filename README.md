# Food Delivery Profitability Analysis

## Introduction

This project focuses on analyzing and predicting profitability in a food delivery business. The dataset contains various features such as order value, delivery fees, discounts, and commissions. The analysis involves data cleaning, feature extraction, and visualizing profitability under different scenarios, including recommended commission and discount rates.

## Project Structure

The project is structured as follows:

1. **Data Loading and Preprocessing:**
   - **Loading the Data:** Import the dataset and create a copy for analysis.
   - **Initial Inspection:** Check data types, inspect the first few rows, and get an overview of the dataset's shape.
   - **Handling Missing Values and Duplicates:** Remove duplicates and unnecessary columns (e.g., `Order ID`).
   - **Feature Engineering:**
     - Convert `Order Date and Time` and `Delivery Date and Time` to datetime format.
     - Extract discount percentages from the `Discounts and Offers` column.
     - Calculate `Discount Amount` based on the order value and the extracted discount percentage.

2. **Profit Calculation:**
   - **Cost and Revenue Calculation:**
     - Compute `Total Costs` by summing up delivery fees, payment processing fees, discounts, and refunds.
     - Calculate `Revenue` based on the commission fee.
     - Derive `Profit` as the difference between revenue and total costs.
   - **Overall Metrics:** Aggregate data to calculate total orders, revenue, costs, and profit.

3. **Visualization:**
   - **Profit Distribution:**
     - Histogram of profit per order, with a dashed line indicating the mean profit.
   - **Cost Proportion:**
     - Pie chart showing the breakdown of total costs (delivery fee, payment processing fee, discount amount).
   - **Revenue, Costs, and Profit Comparison:**
     - Bar chart comparing total revenue, costs, and profit.

4. **Profitability Analysis:**
   - **Profitable Orders:** Filter the dataset for orders with positive profit.
   - **Average Commission and Discount Percentages:**
     - Calculate the average commission percentage and effective discount percentage for profitable orders.
   - **Simulated Profitability:**
     - Simulate profitability using recommended commission and discount percentages.
     - Recalculate `Simulated Total Costs` and `Simulated Profit` using these values.
     - Visualize the comparison between actual and simulated profitability.

## Key Features

- **Data Preprocessing:**
  - Handling of missing values, duplicates, and irrelevant columns.
  - Feature extraction for discount percentages and discount amounts.

- **Profitability Metrics:**
  - Calculation of total costs, revenue, and profit per order.
  - Aggregation of overall profitability metrics.

- **Visualization:**
  - Histograms, pie charts, and bar charts for understanding cost distribution and profitability.
  - KDE plot to compare actual and simulated profitability.

- **Simulated Profitability:**
  - Analysis of profitability using recommended commission and discount rates.
  - Visualization of profitability improvement scenarios.


## Contributing

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request for review.

