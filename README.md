# Online Retail Dataset Analysis Report

## Project Overview

The dataset includes invoice details, product information, quantities purchased, unit prices, customer identifiers, invoice dates, and countries of purchase. The objective of this project was to understand the dataset, perform data cleaning, conduct exploratory data analysis (EDA), create visualizations, and generate business insights.

## Data Cleaning Process Challenges Encountered

1.	Missing values were found in the CustomerID and Description columns.
2.	The dataset contained 5,268 duplicate records.
3.	Some records had invalid values such as negative or zero quantities and unit prices.
4.	Invoice dates were stored as text and required conversion to datetime format.
5.	Column names and text values required standardization for consistency.

## Actions Taken

1.	Missing CustomerID values were filled using the mode (most frequent value).
2.	Missing Description values were replaced with "Unknown".
3.	Duplicate records were identified and removed.
4.	Invalid quantity and unit price values were removed.
5.	InvoiceDate was converted to datetime format.
6.	Column names were converted to lowercase and text fields were standardized.

## Exploratory Data Analysis Findings

1.	A small number of products accounted for a significant share of total sales volume.
2.	The United Kingdom generated the highest revenue among all countries.
3.	Sales exhibited monthly fluctuations, indicating seasonal purchasing patterns.
4.	Most orders involved small purchase quantities, while a few transactions had exceptionally large quantities.
5.	Customer spending was highly concentrated among a relatively small group of customers.

## Top Insights
### Insight 1
Top 10 products account for a large portion of total sales, indicating strong customer preference for specific items
### Insight 2
The United Kingdom generates the highest revenue among all countries.
### Insight 3
Sales increase significantly during certain months, showing seasonal purchasing behaviour.
### Insight 4
Most orders contain small quantities, while a few orders are exceptionally large.
### Insight 5
A small number of customers contribute a large share of total revenue.

## Conclusion

The dataset was successfully cleaned and analyzed. The findings provide valuable insights into customer behavior, product performance, revenue distribution, and sales trends. These insights can support data-driven decision-making for inventory management, marketing campaigns, and customer relationship strategies.
