# Supermarket Sales Data Analysis

## Overview
This project analyzes supermarket sales data to uncover key insights and trends. It involves cleaning the dataset, performing exploratory data analysis (EDA), and visualizing findings to answer business-related questions such as branch performance, customer behavior, and sales trends.

## Features
1. **Data Exploration**:
   - Inspect and summarize the dataset.
   - Check for missing or duplicate data.
2. **Data Cleaning**:
   - Convert date columns to datetime format.
   - Remove duplicates.
   - Validate the integrity of the dataset.
3. **Data Analysis**:
   - Analyze sales performance by branch, product line, gender, and payment method.
   - Investigate time-based trends (e.g., monthly sales).
   - Explore customer ratings and their relationship to sales.
4. **Data Visualization**:
   - Correlation heatmaps to identify relationships between features.
   - Pie and bar charts to highlight sales distributions.
   - Line charts for time-series trends.
   - Boxplots for sales distribution by customer gender.

## Dataset
The dataset consists of 1,000 rows and 17 columns, including:
- **Invoice ID**: Unique identifier for each transaction.
- **Branch**: A, B, or C.
- **City**: City of the branch.
- **Customer type**: Member or Normal.
- **Gender**: Male or Female.
- **Product line**: Product category.
- **Unit price**: Price per unit.
- **Quantity**: Number of units sold.
- **Tax 5%**: Tax applied to the transaction.
- **Total**: Amount including tax.
- **Date/Time**: Transaction date and time.
- **Payment**: Cash, Ewallet, or Credit card.
- **COGS**: Cost of goods sold.
- **Gross margin percentage**: A constant value.
- **Gross income**: Income from the transaction.
- **Rating**: Customer rating of the supermarket.

## Tools and Libraries
- **Python Libraries**:
  - `pandas`: Data manipulation and analysis.
  - `matplotlib`: Basic visualizations.
  - `seaborn`: Advanced and aesthetic visualizations.

## Key Insights
- **Branch Performance**: Branch C generates the highest revenue.
- **Top Product Line**: Food and beverages have the highest sales.
- **Gender Spending**: Female customers have a higher average spending.
- **Monthly Trends**: January shows the highest sales.
