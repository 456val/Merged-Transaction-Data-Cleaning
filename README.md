# Unlocking Insights from Merged Transaction Data

### Project Overview
This project focuses on analyzing a one-day supply transaction dataset that contained multiple product categories and amounts merged within single cells. The raw dataset was messy, making it difficult to interpret spending patterns and transaction summaries. By cleaning and transforming the data into a structured format, this project highlights the value of data preprocessing in generating actionable business insights.

### Objectives
- Clean and transform merged transaction data into a clear, structured format.
- Align each product category with its corresponding transaction amount.
- Summarize transactions to understand spending patterns across product categories.
- Prepare the data for visualization and interpretation of key metrics.

### Data Cleaning and Transformation Process
The raw dataset had multiple values combined in single cells for both product categories and amounts. The steps taken include:

1. **Splitting merged cells:** Categories and amounts were separated into lists.
2. **Exploding rows:** Each product-category and amount pair was expanded into individual rows to align them properly.
3. **Type conversion:** Transaction amounts were converted to numeric types for accurate analysis.
4. **Aggregation:** Data was grouped by product category to calculate total amounts spent and transaction counts.
5. **Export:** The cleaned and summarized data was saved into a new CSV file for further analysis and visualization.

This process turned messy raw data into a format suitable for clear analysis and visualization, making insights more reliable and actionable.

### Results
The cleaned dataset allowed the project to generate meaningful summaries:

- **Total Spending by Category:** Categories like Tables, Fasteners, and Binders accounted for the highest spending.
- **Transaction Count:** Office Supplies and Technology had multiple transactions across orders.
- **Visualization:** Horizontal bar charts highlighted categories with the highest total amounts and transaction volumes.
- **Statistics:** Summary statistics revealed patterns in total amounts spent and transaction counts, including averages, maximums, and minimums.

