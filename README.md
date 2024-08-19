# Executive-Sales-Analysis
Documenting Household Essentials

### Project Overview

The "Documenting Household Essentials" project aims to create a comprehensive, user-friendly system for cataloging and managing household items. This project is designed to help users keep track of their essential items, manage inventory, and streamline household management tasks. By leveraging modern technology, this project will provide an efficient solution to avoid duplication, reduce waste, and ensure that necessary items are always on hand.

![Screenshot 2024-08-19 121928](https://github.com/user-attachments/assets/b58e37ab-d585-484f-923f-761dea631302)

### Data source

The primary dataset used for this analysis is the "Executive_Sales_Reporting" file, containing detailed information about each sale made by the company.

### Tool

- Excel - Data cleaning: Cause this is a critical step in the data analysis pipeline. [Download here](https://microsoft.com)
- VLOOKUP - Looks for a value in the leftmost column of a table, and then returns a value in the same row from a column you specify.
- Snipping - for capturing images and importing it into GITHUB.

### Data Quality Assessment & Cleaning 

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Model development

VLOOKUP: To bring in data from another sheet. Example: "=VLOOKUP([@Salesteamindex],Table3,2,FALSE)" its a reference to the brought in "Executive_Sales_Reporting" file.

### Exploratory Data Analysis

- What is the sum of unit cost by product name?
- What is the sum of order quantity?
- Who are the top 10 customers?
- What are the sales region?
- What's the product by unit price?
- What's the sales team by unit by unit price?
- What are the store type by order quantity?
- What's the product name by store population?

### Result and findings 

- Sum of order quantity: The total order quantity indicates that clocks are exceeding the order volume by 2,775 units, while wall frames are ranked lowest among the top 10 items ordered.
- Sum of unit cost by product name: The total unit cost analysis reveals that clocks have the highest expenditure at $140,593 due to their high order volume, while collectibles have the lowest cost at $126,437
- Top 10 store type customers: Among the top 10 customer types, the leading store, located in the city, has placed 87,285 orders, while the Metropolitan Government ranks lowest with 214 orders.
- Sales region: In terms of sales regions, the Midwest is achieving the highest sales, accounting for 31% of total sales, while the West region is generating the lowest sales.
- Product by unit price: In terms of unit price, clocks have the highest average selling price, exceeding other products by 21%, while phones have the lowest average selling price, trailing by 19%.
- Sales team by unit price: Among the sales team members, Paul Holmes leads with the highest unit sales price, achieving $328,637, while Shawn Wallace has the lowest unit sales price at $311,658.
- Store type by order quantity: Among store types, city locations generate the highest sales with an 80% share of total order quantities, while borough locations contribute the least.
- Product name by store population: In terms of store population usage, phones are the leading product, generating $176,684,399 in revenue, while cocktail glasses rank the lowest.

### Recommendations

1. For Clocks:
- Inventory Management: Ensure that inventory levels for clocks are adequate to meet the higher demand and consider increasing stock if this trend continues.
- Sales Analysis: Analyze the factors contributing to the high demand for clocks, such as promotions or seasonal trends, and adjust marketing strategies accordingly.
2. For Wall Frames:
- Promotional Efforts: Increase marketing and promotional activities to boost interest and sales in wall frames.
- Product Review: Evaluate the product range and pricing of wall frames to ensure they meet customer preferences and competitive standards.

1. For Clocks:
- Cost Analysis: Examine the cost structure for clocks to identify any areas where expenses can be optimized. This may include negotiating with suppliers or evaluating the cost-effectiveness of production processes.
- Pricing Strategy: Review the pricing strategy for clocks to ensure that it aligns with the high demand and contributes to profitability.
2. For Collectibles:
- Cost Evaluation: Assess the cost structure for collectibles to determine if there are opportunities to reduce costs or improve margins.
- Market Strategy: Since collectibles have a lower cost and possibly lower sales volume, consider strategies to increase their visibility and attractiveness to boost sales. This could include targeted promotions or expanding the product line.






