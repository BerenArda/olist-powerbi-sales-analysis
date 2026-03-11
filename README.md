# olist-powerbi-sales-analysis
Power BI dashboard analyzing the Olist Brazilian E-commerce dataset with data cleaning, data modeling and DAX measures.

# Olist E-Commerce Sales Analysis (Power BI Project)

## Project Overview

This project focuses on analyzing the **Olist Brazilian E-commerce Public Dataset** obtained from Kaggle.  
The main objective of this study is to transform raw e-commerce data into meaningful insights by applying **data cleaning, data modeling, DAX calculations, and data visualization techniques using Microsoft Power BI**.

The project demonstrates the complete data analysis workflow including **data preparation, transformation, modeling, metric creation, and dashboard design** in order to extract business insights from the dataset.

---

## Dataset

The dataset used in this project is the **Olist Brazilian E-commerce Public Dataset**, which contains information about orders, customers, sellers, products, payments, and reviews from a Brazilian e-commerce platform.

Dataset source:

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## Data Preparation and Cleaning

A comprehensive data cleaning and preparation process was performed using **Power Query in Microsoft Power BI**.

The following steps were applied during the data preparation stage:

- Unnecessary tables and columns were removed to simplify the data model
- Duplicate records were identified and removed
- Missing values (null values) were reviewed and handled where necessary
- Column data types were checked and converted to appropriate formats
- Text fields were cleaned using **Trim** and **Clean** functions to remove unnecessary spaces and invalid characters
- Some categorical values originally in Portuguese were translated into English to improve dashboard readability

These steps ensured that the dataset was **consistent, structured, and ready for analysis**.

---

## Data Modeling

After the cleaning process, the next step was creating the **data model**.

Relationships were established between tables that logically interact with each other, such as:

- Orders
- Customers
- Order Items
- Products
- Sellers
- Payments
- Reviews

During this stage, special attention was given to **relationship types (one-to-many and many-to-one)** and the **direction of filtering** to ensure accurate analysis results.

A well-structured data model is essential for efficient analysis and accurate metric calculations.

---

## DAX Measures

To perform business analysis, several **DAX measures** were created and organized in a dedicated **Measures table**.

The main metrics created in this project include:

- Total Revenue
- Total Orders
- Total Products Sold
- Total Customers
- Revenue per Customer
- Average Order Value
- Average Review Score
- Average Delivery Days

These measures allow the dashboard to dynamically calculate and display key business metrics.

---

## Dashboard

Using the prepared data model and calculated measures, multiple **interactive dashboard pages** were created in Microsoft Power BI.

The dashboards focus on analyzing different aspects of the business, including:

- Overall sales performance
- Category and product revenue distribution
- Payment method usage
- Customer satisfaction based on review scores
- Delivery performance and logistics insights

Visualizations such as **bar charts, line charts, treemaps, KPI cards, and slicers** were used to create an interactive analytical environment.

---

## Key Insights

Several insights were derived from the analysis, including:

- Revenue trends over time
- Categories generating the highest revenue
- Most frequently used payment methods
- Average customer satisfaction levels
- Delivery performance across orders

These insights provide a quick overview of the business performance and help identify potential areas for improvement.

---

## Tools Used

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Kaggle Dataset

---

## Dashboard File

Due to GitHub file size limitations, the **Power BI (.pbix) dashboard file** is available in the repository **Releases section**.

Download the dashboard file from:

Releases → Power BI Dashboard


## Dashboard Preview

### Modelling
<img width="1533" height="795" alt="Modeling" src="https://github.com/user-attachments/assets/0c886699-4b3c-4f9d-85ba-320780cab2b8" />

### Execute Overview
<img width="1413" height="797" alt="Execute_Overview" src="https://github.com/user-attachments/assets/77250d24-57af-4842-9546-f0a22e810c09" />

### Sale Analysis
<img width="1410" height="793" alt="Sale_Analysis" src="https://github.com/user-attachments/assets/6e13804b-557d-4ab9-94cb-21dfde16299d" />

### Customer & Delivery Insights
<img width="1406" height="791" alt="Customer Delivery_Insights" src="https://github.com/user-attachments/assets/efcc7dfe-e845-4ea0-9304-7c13af8854c4" />








