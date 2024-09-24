# Sales Data Analysis

This project provides a comprehensive analysis of a dataset containing sales information for various products, segmented by consumer and corporate groups. The main goal is to gain insights into sales and profit patterns, understand segment behaviors, and evaluate product performance.

## Overview of the Code Flow:

1. **Loading Data and Basic Inspection**:
   - The dataset `sales.csv` is loaded into a pandas DataFrame.
   - Basic details such as the shape, column types, and missing values are examined.

2. **Data Preprocessing**:
   - The 'Transaction Date' column is converted to datetime format for easier analysis.
   - Missing values are identified and summarized to understand data completeness.

3. **Descriptive Statistics**:
   - Key descriptive statistics (mean, median, standard deviation) are calculated for numerical columns, specifically for Sales and Profit.
   - Skewness is computed to analyze the distribution of the data.

4. **Data Filtering and Grouping**:
   - Data is filtered based on the 'Segment' column to focus on specific groups (e.g., consumers).
   - Grouping is performed by 'Product Name' and 'Segment', allowing for aggregation of Sales and Profit data (sum, mean, median).

5. **Visualization**:
   - A bar chart visualizes the frequency of product names in the dataset.
   - A pie chart illustrates the sales distribution among different products.
   - A time-series plot presents sales data trends over time.

6. **Indexing and Grouping by Segment**:
   - The DataFrame is re-indexed using the 'Segment' column for better data access and manipulation.

## Getting Started

1. Clone the repository.
2. Ensure you have the necessary libraries installed: `pandas`, `matplotlib`, `seaborn`.
3. Run the analysis by executing the provided Jupyter Notebook or Python script.

## Conclusion

This analysis aims to provide actionable insights that can help in making informed decisions related to product offerings and marketing strategies based on consumer and corporate segment behaviors.

