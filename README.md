# Superstore Sales & Profitability Analysis

## Project Overview

This project analyzes the Superstore dataset using Microsoft Excel to evaluate sales performance, profitability, discount behavior, regional performance, product performance, and customer segments.

The objective was to identify key drivers of profitability and uncover business areas where performance could potentially be improved.

The project covers the full analytics workflow, including data cleaning, exploratory analysis, PivotTables, data visualization, business insights, and the development of an interactive style Excel dashboard.

## Tools Used

- Microsoft Excel
- Excel Tables
- PivotTables
- PivotCharts and standard charts
- Excel formulas and calculated metrics

## Business Questions

The analysis focused on the following business questions:

1. Which product categories generate the most sales and profit?
2. Which sub-categories are driving Furniture's low profitability?
3. How do discount levels relate to profitability?
4. How does sales and profitability performance differ across regions?
5. Which individual products are the strongest and weakest performers?
6. How have sales and profit changed over time?
7. Are there observable seasonal patterns in monthly sales?
8. Which customer segments generate the most sales and which achieve the highest profit margins?

## Data Cleaning & Preparation

Before beginning the analysis, the dataset was reviewed and prepared in Excel to ensure that the key fields were suitable for analysis.

Key cleaning and validation steps included:

- Converted the dataset into an Excel Table for structured analysis.
- Checked key analytical fields for missing values, including Order Date, Sales, Quantity, Discount, Profit, Category, Sub-Category, and Region.
- Identified and removed one duplicate record, resulting in 9,993 records for analysis.
- Verified that Order Date and Ship Date were recognized as valid date fields.
- Validated Quantity and Discount values and checked for invalid or unexpected values.
- Identified that the original Sales and Profit columns were stored as text because they contained currency symbols and thousands separators.
- Created numeric Sales and Profit fields using Excel formulas so that the values could be used correctly in calculations and PivotTables.
- Created a Shipping Days field from Ship Date and Order Date and confirmed that shipping times ranged from 0 to 7 days with no negative values.
- Investigated potential sales outliers using the IQR method rather than automatically removing them.
- Retained valid high-value transactions after confirming that they represented plausible business records rather than data-entry errors.
