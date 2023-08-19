# Online-Retail-Insight-Forecast 🛍️
Analyzed an e-commerce dataset to clean data, segment customers using RFM, and forecast sales trends. Addressed missing values, used time series decomposition for sales patterns, and provided recommendations for improved customer engagement and strategy.

## About the Project 📄

The goal of this analysis is to derive actionable business insights from an online retail dataset. The project includes:
- Data Cleaning and Preprocessing
- Customer Segmentation using RFM Analysis
- Time Series Decomposition of Sales
- Predictive Modeling and Evaluation

## Dataset Description 📊

The dataset is sourced from [Online Retail](https://doi.org/10.24432/C5CG6D). It encompasses transactional data, detailing purchases made by customers over a period of time.
Key columns include:

- `InvoiceNo`: Invoice number, a unique identifier for each transaction.
- `StockCode`: Product code.
- `Description`: Product description.
- `Quantity`: Quantity of products in each transaction.
- `InvoiceDate`: Timestamp of the transaction.
- `Price`: Price per unit of the product.
- `CustomerID`: Unique identifier for each customer.
- `Country`: Country of the customer.

## Key Findings 🔍

- **Customer Segmentation**: Identified key customer segments, including 'Champions', 'Loyal Customers', and 'At Risk' groups.
- **Sales Trends**: Seasonal patterns in sales, aiding in forecasting efforts.
- **Predictive Modeling**: Multiple regression models, with the Linear Regression model standing out as the top performer.

For a detailed look into the analysis, check out this [Jupyter Notebook](https://nbviewer.org/github/DrRuin/Online-Retail-Insight-Forecast/blob/main/Online-Retail-Insight-Forecast.ipynb)
