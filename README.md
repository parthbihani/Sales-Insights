# Sales Insights Dashboard

## Project Overview

This Power BI dashboard was designed to help AtliQ Hardware gain deeper insights into their sales trends. The goal was to automate the process of gathering and visualizing sales data, reducing manual data handling, and unlocking previously unseen sales insights. This project helped the sales team identify performance patterns and focus on key areas for growth.


### Steps followed 

 - Step 1 : Gathered sales data from relevant sources and imported it into Power BI.

 - Step 2 : Used Power Query Editor to clean and preprocess the data, handling missing values and correcting data types.

 - Step 3 : Created relationships between tables to ensure accurate data visualization.

 - Step 4 : Defined DAX measures for key metrics like total revenue, profit margin, and sales quantity.

Following DAX expression was written for creating Total Revenue

        Total Revenue = SUM(transactions1[sales_amount] )
    
A card visual was used to represent Total Revenue

![TotalRev](https://github.com/user-attachments/assets/4363e53a-e934-4e6a-ba9f-59aa89629610)


Following DAX expression was written for creating Sum of Sales quantity

        Sales Qty = SUM(transactions1[sales_qty])

 A card visual was used to represent Sales Qty

![SalesQty](https://github.com/user-attachments/assets/426b8b5e-2f7e-4afc-a993-1c87c7e4a2eb)


Following DAX expression was written for creating Total Profit margin

        Total Profit Margin = SUM(transactions1[profit_margin])

![TPM](https://github.com/user-attachments/assets/b698524d-e767-442d-8803-58ce02683a60)

        
 - Step 5 : Designed interactive charts and visuals such as bar charts, pie charts, line graphs, and tables to represent data effectively.

Following are some charts in the Dashboard

This is the Revenue Trend Chart showing the Revenue of company over peroid of time.

![RT](https://github.com/user-attachments/assets/e245e31d-2943-4e61-b336-c0e067662e51)

        
This is the Pie Chart showing the Zone wise distribution of Revenue

![pie](https://github.com/user-attachments/assets/6116122f-33b7-4edd-b84a-6d57151387a9)


 - Step 6 : Implemented slicers for time-based analysis, product selection, and market filtering.

Following image shows the series of Years from which user can select any year to get that particular Year's data.

![year](https://github.com/user-attachments/assets/1be540eb-1196-43a7-a28e-09b69310b85d)

 
 - Step 7 :  Customized visuals and layout to enhance readability and user experience.
 
 
 - Step 8 : Tested the dashboard for functionality, ensuring interactivity and data accuracy.
 

# Snapshot of Dashboard 

Page 1

![page1](https://github.com/user-attachments/assets/fab46ea3-1552-48d0-8923-80e48739eaf7)


Page 2

![page2](https://github.com/user-attachments/assets/15f176a2-9028-493e-b182-95331c814fd9)

 
# Key Features

 - Total Revenue, Sales Quantity, and Profit Margin: Displays aggregate values for revenue, sales volume, and total profit margin.

 - Sales Analysis by Product Code: Highlights the most sold products by quantity.

 - Revenue Contribution by Market: Breaks down the contribution of different cities/regions to overall revenue.

 - Profit Margin Analysis: Compares the profit contribution of various markets to their revenue.

 - Revenue Trends: Shows revenue and profit margin trends over time to visualize growth or decline.

 - Revenue by Zone: A pie chart illustrating the percentage of revenue contributed by different geographical zones (North, Central, South).

 - Top Customers: Lists customers based on revenue generated, showing their contribution to overall revenue and profit margins.




# Key Insights

 - Revenue vs. Profitability: Some cities with high revenue contributions, like Delhi NCR, may not always have the highest profitability.

 - Top Products: Specific product codes such as Prod090 and Prod237 are top sellers in terms of quantity.

 - Geographical Analysis: The North zone generates the most revenue, with significant contributions from cities like Delhi NCR.

 - Customer Contributions: Electricalsara Stores is the top customer by revenue and has a notable impact on profit margins.


# How to Use the Dashboard

1. Select Year or Time Period: Filter data by year or specific months using the time slicer to focus on particular periods.

2. Interact with Visuals: Click on different visuals to highlight related data across the dashboard.

3. Analyze Trends: Use the Revenue Trend chart to monitor how revenue and profit margins evolve over time.

           
# Tools & Technologies

1. Power BI: Used for data visualization and interactive dashboard creation.

2. SQL: For data extraction and analysis prior to visualization.
