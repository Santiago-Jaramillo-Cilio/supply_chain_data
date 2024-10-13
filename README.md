# Supply Chain Analysis

This project provides an analysis of key supply chain metrics, focusing on the relationships between shipping times, manufacturing costs, stock levels, and their impact on sales performance. The analysis leverages a dataset containing supply chain information for different product types and includes exploratory data analysis, data visualization, and predictive modeling.

## Project Overview
The goal of this project is to gain insights into how various supply chain factors such as shipping times, manufacturing lead times, and costs influence the number of products sold. Through this analysis, we aim to provide actionable recommendations for optimizing supply chain processes.

## Dataset
The dataset contains information on various products, including:
- **Product Type**
- **SKU**
- **Price**
- **Availability**
- **Number of Products Sold**
- **Revenue Generated**
- **Stock Levels**
- **Lead Times**
- **Manufacturing Costs**
- **Transportation Modes**

The dataset is sourced from internal supply chain records and has been cleaned and processed for analysis.

## Methodology
The project is divided into the following sections:
1. **Data Cleaning**: Handling missing values, data type conversions, and outlier detection.
2. **Exploratory Data Analysis (EDA)**: Visualizing key metrics such as shipping times, costs, and defect rates to understand trends and correlations.
3. **Predictive Modeling**: Using linear regression to predict how reducing shipping times and other factors impact the number of products sold.
4. **Correlation Analysis**: Investigating the relationships between manufacturing lead times, costs, and defect rates.

## Key Findings
1. **Shipping Times**: Reducing shipping times is correlated with an increase in the number of products sold.
2. **Manufacturing Costs**: Higher manufacturing costs, in some cases, are associated with increased sales, likely due to product quality improvements.
3. **Stock Levels**: Ensuring optimal stock levels is crucial for meeting demand and avoiding lost sales.

## Technologies Used
- **Python**: For data analysis and modeling.
- **Pandas**: For data manipulation and processing.
- **Seaborn/Matplotlib**: For data visualization.
- **Scikit-learn**: For predictive modeling.
- **Jupyter Notebooks**: For interactive coding and analysis.

