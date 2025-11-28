# Sales-Insights-Brick-motor-business-

This dashboard is create to understand AtliQ hardware goods sales trend.
• The final dashboard was effective at displaying the sales trend of AtliQ hardware, allowing users to understand
the data and make informed decisions.
• This dashboard could help in increasing the revenue at least by 7% in the next quarter. 

The first step involve simple cleaning data using MySql. Then we use Power BI to connect to the same MySQL database, perform ETL (Extract, Transform, Load) operations, clean the data, and prepare it for analysis.

Data Cleaning in Power Query involve:

Filter out irrelevant regions (e.g., New York, Paris).

Remove invalid sales amounts (0 or negative values).

Handle hidden characters or inconsistencies in data.

Currency Normalization

Convert all sales amounts to a single currency (INR) using a conditional column.

Apply formulas to handle USD to INR conversions and ensure data consistency.

Finalizing Transformations

Apply all changes and load clean data into Power BI.

Verify transformations: filtered markets, valid sales amounts, normalized currency.

Creating base measures (Revenue, Sales Quantity), basic visuals and formatting

Adding year slicer, monthly revenue visualization, regional sales analysis

Top 5 customers and products by revenue, revenue trend line chart
