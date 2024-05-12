# PacBook Data Warehouse

PacBook, a company specializing in selling various books, aims to separate their transaction storage from the storage intended for analysis. As a Data Engineer, you are tasked with building a Data Warehouse using the Dimensional Model and performing ELT processes to transfer data from the data source to the data warehouse. 
You will be provided with their current transaction dataset, which you'll explore to gain a deeper understanding of the data before designing the data warehouse model.
Stakeholders have outlined several analytical matrices they wish to explore, including:
Monthly sales trends
A list of books and their total sales quantity over time
Customer behavior: Average time taken for repeat orders
Customer segmentation: Identifying distinct groups of customers based on their purchasing behavior, demographics, or other criteria.
Profitability analysis: Determining the profitability of different products, customer segments, or sales channels to optimize business strategies.
Sales forecasting: Predicting future sales trends and demand to optimize inventory levels and resource allocation.
The constructed Data Warehouse should be able to address these analytical questions.

Several tasks need to be completed in this Final Project:

Requirements Gathering & Proposed Solution
You will be required to understand the problem given by stakeholders, and then provide a solution based on the problem.

Designing Data Warehouse Model
Based on the results of Requirements Gathering & Proposed Solution, you will create a dimensional model of the Data Warehouse, including:
Dimensional Tables
Fact Tables
Use at least 2 types of fact tables
Slowly Changing Dimension Strategy

ELT Implementation
You will create an ELT Workflow and implement it using Python, Luigi, and DBT. 
Create Database include schema staging and data warehouse
You can use python to extract Data from Data Source to Schema Staging
Then, use DBT to transform and load data from Schema Staging to Schema Data Warehouse

Testing Scenario
To ensure the robustness of the pipeline, a testing scenario will be provided to verify if the pipeline can run according to the given scenario.

Documentation
A good Data Engineer can create a summary or documentation regarding the Data Warehouse and Pipeline created, including the solution provided, architecture, Data Warehouse design, pipeline design, how to run the pipeline, etc.

This project provides you with an opportunity to apply the knowledge and skills you have acquired in the Data Storage course.
