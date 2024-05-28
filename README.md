Overview
Adventure Works, a renowned bike manufacturer and seller, provided their sales and returns data for analysis. This end-to-end project involved data importing, cleaning, modeling, and visualization using Microsoft Power BI Desktop.

Data Cleaning
The raw dataset, provided in .csv format, was imported directly into Power BI. A total of 8 files were imported, each representing a distinct table. The primary focus was on Sales and Returns data. The cleaning process included:

Ensuring columns were appropriately titled.
Correcting data types.
Checking for missing data (none was found).
Identifying potential relationships between tables.

Data Modeling
After verifying data accuracy and consistency, a data model was created:
Established primary tables: 'Sales Data' and 'Returns Data'.
Defined relationships, primarily one-to-many.
The completed model is illustrated below for better understanding.

DAX Functions
With table relationships in place, DAX functions were utilized to analyze the dataset. Key DAX functions used include:

ITERATOR FUNCTIONS (SUMX): Evaluates an expression for each row and aggregates results.
CALCULATE(): Overrides filters to create new filter contexts, useful for metrics like Previous Month's Orders, Revenue, Profit, Returns, and Overall Average Price.
RELATED(): Pulls data from different tables with established relationships.
Date Functions (DateAdd, DATESINPERIOD): Essential for calculating metrics like 90-Day Rolling Profit and monthly comparisons.
Measures created for this project were organized into a dedicated Measure Table.

Data Visualization
The report includes four visualization pages:

•	Executive Dashboard: Key performance indicators and summary metrics.
•	Map: Geographical representation of sales data.
•	Product: Detailed analysis of product performance.
•	Customer Detail: Insights into customer behavior and demographics.
Each visualization page offers a unique perspective, enabling comprehensive data analysis and informed decision-making.

Conclusion
This project demonstrates a thorough process of data cleaning, modeling, and visualization using Power BI, providing valuable insights into Adventure Works' sales and returns. The use of DAX functions and clear visualizations ensures a robust analysis, aiding in strategic planning and operational efficiency.

For more details, check out the full Power BI report.
