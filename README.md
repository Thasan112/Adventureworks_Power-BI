🚴 Adventure Works Sales & Returns Analysis – Power BI Project
📊 Overview
Adventure Works, a renowned bike manufacturer and retailer, provided their Sales and Returns data for analysis. This end-to-end data project involved importing, cleaning, modeling, and visualizing data using Microsoft Power BI Desktop.

🧹 Data Cleaning
The raw dataset consisted of 8 CSV files, each representing a distinct table. The cleaning process was conducted within Power BI and focused on:

Renaming columns for clarity.

Correcting and standardizing data types.

Verifying the absence of missing data.

Identifying and preparing relationships across tables.

The primary focus was on the Sales and Returns tables.

🧱 Data Modeling
After data cleaning and validation:

Established primary tables: Sales Data and Returns Data.

Created one-to-many relationships between tables.

Designed a logical data model to support analytical goals.

📌 A visual representation of the data model was created within Power BI for reference.

🧠 DAX Functions & Measures
To extract actionable insights, DAX (Data Analysis Expressions) functions were used extensively. Key functions include:

SUMX: Iterates over a table to calculate and sum row-wise values.

CALCULATE(): Creates custom filter contexts for dynamic metrics (e.g., previous month's sales, profit, return rate).

RELATED(): Pulls related values from other tables.

Date Functions:

DATEADD, DATESINPERIOD for calculating:

90-Day Rolling Profit

Month-over-Month comparisons

➡️ All custom measures were centralized in a dedicated Measure Table for easy access and maintenance.

📈 Data Visualization
The Power BI report was organized into four visualization pages, each offering unique business insights:

 
Dashboard
High-level KPIs (Sales, Profit, Returns, Avg. Price)

Map

Geographic breakdown of sales and returns.

Product Performance

Insights by product category, model, and returns.

Customer Detail

Behavior, demographics, and return trends by customer.

These dashboards provide stakeholders with a 360° view of business performance and support data-driven decision-making.

🧰 Tools Used
Microsoft Power BI Desktop

DAX (Data Analysis Expressions)

Power Query (M Language)

📎 Summary
This project demonstrates an end-to-end approach to business data analysis using Power BI. From data ingestion to interactive dashboards, the focus was on uncovering insights and delivering a clear, actionable story through data.
