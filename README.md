# Predict Future Sales Challenge by Kaggle
This project aims to analyze the sales data and uncover meaningful insights and patterns. The project makes use of R programming and various data analysis and visualization techniques.

## Data
The data used in this project is provided as three CSV files: sales_train.csv, items.csv and test.csv. The data includes information about the date, item, item category, item price, and number of items sold in a given day.

## Pre-processing
The data is first merged and cleaned, then feature engineering is performed to create new variables such as year, month, day, and weekday. The data is then transformed to obtain the monthly sales for each shop and item. The missing values are then checked and dealt with accordingly.

## Exploratory Data Analysis
The exploratory data analysis includes generating summary statistics and visualizations to gain insight into the data. The visualizations include:

1. Ranking of shop sales
2. Sales of items by category
3. Best-selling items by category
4. Time-series analysis of monthly sales
## Conclusion
The exploratory data analysis provides valuable insights into the sales data, such as the best-selling items by category, and the ranking of shop sales. It is also possible to see the trends in sales over time and the impact of promotions and events on sales. This information can be used by the company to make informed decisions about inventory management, product development, and marketing strategies.

Tools and Libraries
The project uses R programming language and the following libraries:

dplyr,
lubridate,
ggplot2,
reshape,
gbm,
