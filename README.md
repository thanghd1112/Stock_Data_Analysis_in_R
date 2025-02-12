# Stock Analysis and Forecasting Using R

## Overview
This project focuses on analyzing and predicting stock trends of Vingroup (VIC) over the past decade (from January 2, 2014, to March 12, 2024). Using R programming and the `vicStock.csv` dataset, the study explores various statistical and financial techniques to better understand stock market behavior and predict its trends.

## Objectives
The project aims to:

1. **Deepen knowledge of R tools for stock analysis:** Learn and apply popular R libraries such as `quantmod`, `forecast`, and `prophet` to handle, visualize, and analyze stock data.
2. **Analyze VIC stock data:** Investigate statistical features, trends, and market structure from the historical VIC stock dataset.
3. **Develop predictive models in R:** Use historical data and market factors to create reliable forecasting models for financial decision-making.

## Key Content

### 1. Introduction to R and Stock Data
- An overview of R programming in financial analysis.
- Introduction to essential R libraries like `quantmod`, `TTR`, and `forecast`.
- Guide on retrieving and processing stock data for analysis.

### 2. Statistical Analysis of Stock Data
- Conducting exploratory data analysis (EDA) to uncover trends and patterns in VIC stock data.
- Applying statistical methods and visualization tools to explore price volatility and market trends.

### 3. Building Predictive Models
- Implementing various forecasting techniques:
  - **ARIMA:** For time-series modeling and prediction.
  - **Prophet:** To capture seasonality and trend components for better accuracy.
- Evaluating model performance using metrics like MAE and RMSE.

### 4. Summary and Conclusion
- Summarizing findings and insights gained from the analysis.
- Highlighting the applicability of R-based techniques in stock forecasting.

## Dataset
The dataset, `vicStock.csv`, contains historical stock data of Vingroup (VIC) from January 2, 2014, to March 12, 2024. Key features include:
- Opening price
- Closing price
- High and low prices
- Trading volume

## Limitations
- The study is confined to analyzing data from a specific time range, which may not capture all market dynamics.
- Financial markets are inherently unpredictable, and forecasting models might face limitations due to market volatility and external factors.

## How to Use This Repository

### Prerequisites
Install the required R packages:
```R
install.packages(c("quantmod", "forecast", "prophet", "ggplot2", "dplyr"))
```

### Running the Code
1. Load the dataset:
   ```R
   vic_data <- read.csv("vicStock.csv")
   ```
2. Explore the data and visualize trends.
3. Implement forecasting models as provided in the `StockAnalyst_R.ipynb` notebook.

### Output
- Visualizations of stock trends.
- Forecasted stock prices for the next 30 days.

## Repository Structure
- **`StockAnalyst_R.ipynb`**: Jupyter Notebook containing R scripts for stock data analysis and forecasting.
- **`vicStock.csv`**: Dataset used for the project.
- **`README.md`**: Documentation of the project.

## Conclusion
This project demonstrates the use of R in financial data analysis and forecasting. By applying statistical and machine learning techniques, it provides a comprehensive toolkit for understanding and predicting stock market trends.

---

For more details, refer to the `StockAnalyst_R.ipynb` notebook.