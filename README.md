
# Retail Sales Intelligence Data Agent on Databricks

## Project Overview

This project focuses on building a Retail Sales Intelligence Data Agent using Databricks. The objective was to create an AI-powered assistant capable of answering business questions about retail sales performance using natural language.

The agent transforms transaction data into clear business insights that can support decision-making without requiring users to write SQL queries.


## Tools Used

- Databricks
- Databricks Data Agent
- SQL
- GitHub
- CSV Retail Sales Dataset


## Dataset Description

The dataset contains retail transaction records with the following fields:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

The dataset was registered in Databricks as:

`1772863649520_retail_sales_dataset`


## Agent Objective

The Retail Sales Intelligence Agent helps business owners, managers and decision-makers understand:

- Revenue performance
- Product category performance
- Customer purchasing behaviour
- Sales trends over time

The agent provides insights using only available dataset information and avoids unsupported assumptions.


## Project Steps Completed

1. Uploaded retail dataset into Databricks
2. Reviewed dataset structure and data quality
3. Prepared the retail_sales_data table
4. Created and connected the Data Agent
5. Developed custom agent instructions
6. Tested the agent with 10 business questions
7. Validated three agent responses independently
8. Documented findings and insights
9. Uploaded project materials to GitHub
10. Submitted repository link


## Example Questions Tested

- What is the total revenue generated?
- Which product category generated the highest revenue?
- Which category has the highest sales volume?
- Which gender contributes the most revenue?
- Which age group has the highest average spending?
- How does sales performance change over time?
- Which category should management focus on?
- Is sales volume aligned with revenue performance?
- Is data available for future periods?
- Which customers are likely to purchase again?


## Key Insights

- Total revenue generated: $456,000
- Electronics generated the highest revenue ($156,905)
- Clothing achieved the highest sales volume
- Female customers contributed slightly higher revenue
- May 2023 was the strongest sales month
- September 2023 recorded the lowest sales performance


## Validation

Three responses were independently validated using SQL queries.

The validation showed that:
- Revenue calculations were accurate
- Product ranking was correct
- Predictive customer analysis required caution due to limited historical purchase data

## Conclusion

The project demonstrated how Data Agents can transform retail transaction data into business-friendly insights. The exercise also highlighted the importance of validating AI-generated outputs and understanding dataset limitations before making business decisions.
