# Online Retail — Full Data Analysis Project

### Python • Pandas • Matplotlib • Seaborn • Plotly

## Project Overview

This project focuses on performing a complete data analysis of an Online Retail dataset obtained from Kaggle.

The main goal is to investigate and clean the dataset, perform exploratory data analysis (EDA), identify sales patterns, and discover valuable business insights that can support better decision-making.

## Dataset Information

- **Dataset:** Online Retail Dataset
- **Source:** [Kaggle — Online Retail Dataset](https://www.kaggle.com/datasets/vijayuv/onlineretail)
- **Data Type:** Retail Transaction Data
- **Main Features:**
  - InvoiceNo
  - StockCode
  - Description
  - Quantity
  - InvoiceDate
  - UnitPrice
  - CustomerID
  - Country

## Project Objectives

- Understand the structure and characteristics of the dataset.
- Investigate missing values and duplicate records.
- Identify cancellation invoices and unusual transactions.
- Clean and preprocess the data using Pandas.
- Create new features for revenue and date analysis.
- Analyze product and country performance.
- Explore monthly sales and customer purchasing behavior.
- Build meaningful visualizations.
- Generate actionable business recommendations.

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Project Workflow

### Part 1 — Data Understanding & Initial Inspection
- Display the first and last rows.
- Explore dataset dimensions and memory usage.
- Inspect column names and data types.
- Generate descriptive statistics.
- Analyze unique values and cardinality.

### Part 2 — Data Quality Investigation
- Identify missing values and their percentages.
- Visualize missing data.
- Investigate duplicate records.
- Analyze invoice cancellations.
- Examine negative and zero quantities.
- Investigate unusual unit prices.
- Check product descriptions and customer information.

### Part 3 — Data Cleaning & Feature Engineering
- Define a data cleaning strategy.
- Remove exact duplicate records.
- Handle missing values appropriately.
- Preserve valid returns and cancellation records for investigation.
- Convert columns to appropriate data types.
- Calculate transaction revenue.
- Extract date features such as Year, Month, MonthName, DayName, and Hour.

### Part 4 — Pandas Business Analysis
- Identify the top 10 products by quantity sold.
- Identify the top 10 products by revenue.
- Compare product rankings.
- Analyze country performance.
- Calculate total revenue and average invoice value.
- Explore monthly revenue trends.
- Analyze customer spending behavior.
- Investigate invoice-level performance.

### Part 5 — Matplotlib Visualizations
- Top 10 products by revenue using a horizontal bar chart.
- Monthly revenue trend using a line chart.

### Part 6 — Seaborn & Plotly Visualizations
- Revenue distribution using boxplots.
- Outlier analysis.
- Correlation heatmap with annotations.
- Interactive monthly revenue chart using Plotly.
- Business insights based on visualizations.

## Data Cleaning Decisions

- Exact duplicate records were removed to prevent double counting.
- Records with missing CustomerID were retained for general sales analysis.
- Records with missing Description were retained when other transaction information remained useful.
- Cancellation invoices were preserved for transaction history.
- Negative quantities were retained because they may represent product returns.
- Zero and negative prices were investigated rather than automatically removed.
- InvoiceDate, CustomerID, Quantity, and UnitPrice were converted to appropriate data types.

## Key Business Insights

The analysis focuses on discovering:

1. The highest revenue-generating products.
2. The countries contributing the most revenue.
3. Monthly sales performance and seasonal patterns.
4. Customer purchasing behavior.
5. The impact of returns and cancellations on sales analysis.

## Business Recommendations

1. Focus on promoting high-performing products to increase revenue.
2. Develop targeted marketing strategies based on country-level sales performance.
3. Monitor returns and cancellations to identify problems and improve customer satisfaction.

## Project Files

- **Jupyter Notebook:** `Online_Retail_Full_Data_Analysis(1).ipynb`
- **Dataset:** `data.zip`
- **Presentation:** Project presentation covering the analysis workflow, findings, and lessons learned.

## Conclusion

This project demonstrates how Python and its data analysis libraries can transform raw retail transaction data into meaningful business insights.

Through data cleaning, exploratory analysis, and visualization, the project provides a better understanding of sales performance, customer behavior, product revenue, and business opportunities.
