# Analyzing Amazon Sales Data

## Project Overview
This project aims to analyze Amazon sales data to extract meaningful insights and key metrics. By leveraging data analysis and visualization techniques, the project provides a deep dive into sales trends, regional performance, and product profitability.

## Objectives
- Extract and load Amazon sales data.
- Clean and transform the data for analysis.
- Conduct exploratory data analysis (EDA) to uncover initial insights.
- Perform detailed analysis to identify key metrics and trends.
- Visualize the findings to support decision-making.

## Table of Contents
1. [Introduction](#introduction)
2. [Tools and Technologies](#tools-and-technologies)
3. [Data Collection](#data-collection)
4. [Data Preprocessing](#data-preprocessing)
5. [Feature Engineering](#feature-engineering)
6. [Data Analysis](#data-analysis)
7. [Visualization](#visualization)
8. [Additional Visualizations and Analysis](#additional-visualizations-and-analysis)
9. [Key Metrics and Relationships](#key-metrics-and-relationships)
10. [Results](#results)
11. [Conclusion](#conclusion)
12. [Limitations](#limitations)

## Tools and Technologies
- **Programming Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Software/Platforms:** Jupyter Notebook, Tableau, Power BI

### Installation Guide
1. Install Python from [python.org](https://www.python.org/).
2. Install necessary libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Optionally, install Jupyter Notebook:
   ```bash
   pip install notebook
   ```

## Project Goals
- Analyze Amazon sales data to uncover trends and key metrics.
- Create visualizations to support data-driven decision-making.
- Provide insights into regional sales performance and product profitability.

## Introduction

### Project Overview
This project aims to analyze Amazon sales data to extract meaningful insights and key metrics. By leveraging data analysis and visualization techniques, the project provides a deep dive into sales trends, regional performance, and product profitability.

### Objectives
1. Extract and load Amazon sales data.
2. Clean and transform the data for analysis.
3. Conduct exploratory data analysis (EDA) to uncover initial insights.
4. Perform detailed analysis to identify key metrics and trends.
5. Visualize the findings to support decision-making.

## Tools and Technologies

### Programming Languages
- Python
- SQL

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Software/Platforms
- Jupyter Notebook
- Tableau
- Power BI

## Data Collection
### Data Sources
The dataset used in this project is obtained from Amazon sales records.

### Data Description
The dataset includes the following columns:
- Region
- Country
- Item Type
- Sales Channel
- Order Priority
- Order Date
- Order ID
- Ship Date
- Units Sold
- Unit Price
- Unit Cost
- Total Revenue
- Total Cost
- Total Profit

## Data Preprocessing
### Data Cleaning
- Ensured all columns have appropriate data types.
- Checked for and handled any missing values, outliers, and inconsistencies (none found in this case).

### Data Transformation
- Converted date columns to datetime format.
- Created new columns for month and year extracted from the Order Date.
- Calculated additional metrics such as Total Revenue, Total Cost, Total Profit, and Gross Margin.

### Exploratory Data Analysis (EDA)
Initial insights were derived using visualizations and descriptive statistics.

## Feature Engineering
### New Features
- Extracted month and year from the Order Date.
- Calculated Gross Margin as a new feature for profitability analysis.

## Data Analysis
### Methods and Techniques
- Used grouping and aggregation techniques to derive metrics.
- Employed various visualization techniques to illustrate findings.

### Detailed Analysis
- Calculated total revenue, gross profit, and gross margin.
- Analyzed sales channel distribution.
- Conducted region-wise analysis of units sold.
- Analyzed sales trends on a monthly and yearly basis.

## Visualization
### Month-wise Sales Trends
Visualize total revenue by month to identify seasonal trends.

### Sales Channel Distribution
Analyze the distribution of sales channels across regions.

### Region-wise Units Sold
Visualize units sold across different regions to identify top-performing regions.

### Year-wise Sales Trends
Analyze sales trends over the years.

### Yearly Month-wise Sales Heatmap
Visualize sales trends across different years and months using a heatmap.

## Additional Visualizations and Analysis
### Profit Margin Analysis
Visualize the distribution and trends of gross margins across different regions or sales channels.

### Time Series Analysis
Explore trends and seasonality in sales over time using time series plots.

### Product Performance Analysis
Identify top-selling products and their performance metrics.

### Customer Segmentation Analysis
Segment customers based on their purchasing behavior and analyze their contribution to sales.

### Correlation Analysis
Explore correlations between different numerical variables in the dataset.

## Key Metrics and Relationships
Analyze key metrics and relationships between attributes, such as the relationship between units sold and total revenue or the impact of the sales channel on revenue.

## Results
### Findings
- **Total Revenue:** $137,348,768.31
- **Gross Profit:** $44,168,198.40
- **Gross Margin:** 36.21%
- **Average Units Sold:** 5128.71

## Conclusion
### Summary
The project successfully analyzed Amazon sales data, uncovering important trends and metrics that can help inform business decisions.

## Limitations
- Data may not capture all aspects of Amazon sales due to limitations in dataset scope.
- Analysis assumes data integrity and completeness, which may affect results if not upheld.
- External factors impacting sales (e.g., market trends, competition) are not directly accounted for in this analysis.
