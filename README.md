# Retail-Sales-Intelligence-Data-Agent

# Project Title

# Retail Sales Intelligence Agent on Databricks

# Project Objective

The objective of this project was to build a Retail Sales Intelligence Agent using Databricks that enables business users to analyse retail sales data through natural language queries. The agent was designed to provide accurate, data-driven insights into sales performance, customer behaviour, product performance, and sales trends while supporting informed business decision-making.

# Tools Used

- Databricks
- Databricks SQL
- Databricks Data Intelligence Agent
- GitHub
- Microsoft Word

# Dataset Overview

The project uses the retail_sales_data table, which contains retail transaction records with the following fields:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

The dataset supports sales, customer, product, and trend analysis.

# Steps Followed

1. Uploaded the retail sales dataset into Databricks.
2. Reviewed the dataset structure, schema, and data quality.
3. Prepared the "retail_sales_data" table by adding descriptions to the table and columns.
4. Created and configured the Retail Sales Intelligence Agent.
5. Developed custom agent instructions.
6. Tested the agent using ten business questions.
7. Validated three responses using SQL queries.
8. Documented the complete project with screenshots.
9. Published the project to GitHub.

# Agent Instructions

The Retail Sales Intelligence Agent helps business owners and managers analyse retail sales using the "retail_sales_data" table. It provides accurate, clear, and actionable insights into revenue, customer behaviour, product performance, and sales trends using natural language. The agent uses only available data, clearly communicates limitations, avoids unsupported assumptions, and provides recommendations only when supported by evidence from the dataset.

# Sample Questions Tested

- What is the total revenue generated from all transactions?
- How many transactions are recorded, and what is the average transaction value?
- Which product category generated the highest revenue?
- Is the category with the highest sales volume also the highest revenue generator?
- Which customer gender contributes the most revenue?
- Which age group has the highest average transaction value?
- How does sales performance change over time?
- Which product category should management focus on?
- Which product category had the highest sales during December 2025?
- Which customers are likely to purchase more next month?

# Key Insights

- Revenue varies across product categories.
- Customer purchasing behaviour differs by gender and age.
- Sales performance changes over time, with distinct high- and low-performing periods.
- Revenue and sales volume do not always follow the same pattern.
- SQL validation confirmed the accuracy of key Data Agent responses.
- The Data Agent appropriately identified situations where available data could not answer a question.

# Conclusion

This project demonstrates how Databricks Data Intelligence Agents can transform retail transaction data into meaningful business insights through natural language. It also highlights the importance of validating AI-generated responses using SQL to ensure reliable, transparent, and evidence-based decision-making in a retail environment.
