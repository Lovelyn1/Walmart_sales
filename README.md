# Walmart_sales Analysis

### Project Overview

This data analysis project aims to provide insights into the sales performance of a retail and wholesale business (Walmart) for 3 months (January, Feburary and March).

### Data Sources

The dataset was gotten from [Kaggle Walmart Sales Forecasting Competition](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting)

### Tools

- MySQL Workbench - Data Cleaning
- MySQL - Data Analysis

### Data Cleaning/Preparation

In the data cleaning phase, the following actions where performed:
1. Data loading and inspection.
2. Adding extra columns to my dataset from the date and time column to simplify the analysis.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- What the over all sales trend ?
- Which product line are top sellers ?
- What are the peak sales perods?
- What gender buys more from the 
  
### Data Analysis

---sql

 SELECT
		city,
        AVG(VAT) AS VAT
	FROM sales
        GROUP BY city
        ORDER BY VAT DESC;
---

### Result/Findings


### Recommendations

### Limitations

### References
