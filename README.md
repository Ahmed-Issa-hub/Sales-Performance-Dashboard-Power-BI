## Sales Performance Dashboard — Power BI 

###  Overview

This project analyzes sales performance using Power BI and Power Query, with a focus on transforming raw sales, product, and budget data into an interactive business dashboard.

The objective is to track sales performance over time, compare product categories and groups, evaluate performance against targets, and identify business areas that may require attention or resource reallocation.

### Business Objectives

The analysis focuses on answering questions such as:

    - How does sales performance change over time?
    - Which product groups generate the strongest and weakest sales results?
    - Which categories contribute the most to total revenue?
    - How does actual sales performance compare with targets or budget?
    - Which products or categories may require additional commercial attention?
    - Are there seasonal patterns that could influence sales planning?

### Data Sources

The project combines multiple Excel data sources:

    - SalesData.xlsx — transactional sales data
    - Product.xlsx — product and category information
    - Budget.xlsx — target and budget data
    - Photos.xlsx — supporting product information

The data was prepared and transformed before being loaded into the Power BI data model.

### Tools & Skills Demonstrated

    - Power BI
    - Power Query
    - DAX Measures
    - Excel
    - Data Cleaning
    - Data Transformation
    - Data Modeling
    - KPI Development
    - Relationship Management
    - Dashboard Development
    - Actual vs. Target Analysis
    - Sales Trend Analysis
    - Product Performance Analysis
    - Business Data Visualization
      
### Key Insights

    - Q4 generated approximately 23% higher sales across the analyzed 2019–2021 period.
    - The Yeasts product group consistently performed approximately 15% below its target.
    - The Food category represented approximately 87% of available products while generating around 62% of revenue.
    - Analysis highlighted opportunities to reconsider resource allocation across products and product groups based on their relative performance.
    - Fifteen low-margin SKUs were identified as potential candidates for further commercial review.
    - The Coffee in Capsules product line showed potential for further growth based on observed sales performance.
    - These findings represent analytical observations from the project dataset and should be validated alongside wider commercial and market context before operational decisions are made.

### Data Modeling & DAX

The project uses a structured Power BI data model that integrates sales, product, and budget data for interactive performance analysis.

A dedicated Calculations table was created to centralize DAX measures and keep the semantic model organized.

Key DAX measures include:

    - Revenue — tracks total sales revenue.
    - Target — represents the assigned sales target.
    - Achievement % — measures actual performance relative to target.
    - Actual vs Target — evaluates sales performance against planned targets.
    - AOV (Average Order Value) — measures average revenue generated per order.
    - Number of Orders — tracks total order volume.
    - QTY — measures total units sold.
    - Diff from LM — compares current performance with the previous month.
    - Diff from LQ — compares current performance with the previous quarter.
    - Ranking — ranks performance across the analyzed business dimensions.
    - Person Revenue % — measures individual revenue contribution as a percentage of total revenue.

Power Query was used for data preparation and transformation before loading the data into the Power BI model.

### Dashboard

The interactive Power BI dashboard provides views of:

    - Overall sales performance
    - Sales trends over time
    - Product and category performance
    - Actual versus target performance
    - Product-level analysis
    - Business KPIs

![Main Dashboard](https://github.com/Ahmed-Issa-hub/Sales-Dashboard-Power-bi/blob/main/Dashboard.png?raw=true)

---


###  Repository Structure

Dashboard.pbix — interactive Power BI dashboard

Dashboard.png — dashboard preview

Raw data/

SalesData.xlsx

Product.xlsx

Budget.xlsx

Photos.xlsx

README.md

---


## Let's Connect!

[LinkedIn](https://www.linkedin.com/in/ahmed-eissa-837691a1/) 




