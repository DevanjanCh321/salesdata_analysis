# Sales Data Analysis Project

## Overview
This project involves performing various data analysis tasks on a sales dataset. The dataset includes information about users, products, and sales transactions.
The analysis includes frequency counts, sales analysis, geographical analysis, correlation analysis, and visualizations to gain insights into the data.

## Dataset
The dataset contains the following columns:
- `User_ID`
- `Cust_name`
- `Product_ID`
- `Gender`
- `Age Group`
- `Age`
- `Marital_Status`
- `State`
- `Zone`
- `Occupation`
- `Product_Category`
- `Orders`
- `Amount`

## Installation
To run the analysis, you need to have Python installed along with the following libraries:
- pandas
- matplotlib
- seaborn

You can install the required libraries using pip:
```bash
pip install pandas matplotlib seaborn

##Analysis and Visualization##
Frequency Counts
Calculate the frequency of categorical variables such as Gender, Age Group, Marital_Status, State, Zone, Occupation, and Product_Category.

**Sales Analysis**
Total Sales: Calculate the total sales revenue.
Sales by Category: Analyze sales by Product_Category and Product_ID.
Sales by Region: Analyze sales by State and Zone.
Top Selling Products: Identify the top selling products.
Geographical Analysis
State-wise Sales: Compare sales across different states.
Zone-wise Sales: Evaluate sales performance across different zones using a pie chart.
Correlation Analysis
Compute and visualize a correlation matrix to find relationships between numerical variables such as Age, Orders, and Amount.

Key Performance Indicators (KPIs)
Total Revenue: The sum of all sales (Amount).
Average Order Value (AOV): Total revenue divided by the number of orders.
Total Number of Orders: The sum of all orders.
Top Selling Products: Products with the highest sales (Amount).
Customer Distribution by Gender: The count of customers by gender.
Customer Distribution by Age Group: The count of customers by age group.
