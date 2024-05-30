# Sales-Dashboard-Project
Excel: For data storage, manipulation, and initial analysis.
I'm thrilled to share my latest project where I developed a comprehensive Sales Dashboard using advanced Excel functions and formulas. This project showcases my skills in data analysis and Excel automation, providing valuable insights into sales performance. The Sales Dashboard project is designed to provide comprehensive insights into the sales performance across different product categories and sales channels. By integrating various data points, the dashboard allows for in-depth analysis and informed decision-making.
Here are some of the key features and formulas used
Key Features & Insights:

VLOOKUP Function:

Formula: =VLOOKUP([@[PRODUCT ID]],MasterData,2,0)
Purpose: This formula is used to fetch product details from the Master Data sheet based on the Product ID, ensuring accurate and up-to-date information.
Dynamic References:

Formula: =[@[MONTH ]]
Purpose: Simplifies the referencing of monthly data, making the dashboard dynamic and easy to update.
Sales Calculation:

Formula: =[@[SELLING PRICE]]*[@QUANTITY]*(1-[@[DISCOUNT %]])
Purpose: Calculates the net sales amount after applying discounts, providing a clear view of revenue.
Cost Calculation:

Formula: =[@[BUYING PRIZE]]*[@QUANTITY]
Purpose: Computes the total cost of goods sold, essential for profitability analysis.
OFFSET Function:

Formula: =OFFSET($S$3,1,0,COUNT($T:$T))
Purpose: Creates dynamic ranges for data analysis, enhancing the flexibility of the dashboard.
Conditional Lookup:

Formula: =IF($N$1=TRUE,VLOOKUP(M3,I:K,3,0),NA())
Purpose: Executes a conditional VLOOKUP based on a specific condition, adding a layer of logic to data retrieval.

Insights
Sales Performance:

Total Sales: $401,411.92
Total Profit: $68,907.92
Profit Margin: 20.72%
Monthly Breakdown:

Highest Sales: April ($20,202.10)
Consistent Growth: Notable increase in sales in the second quarter.
Category Analysis:

Best Performing Category: Category01 with sales of $69,261.95
Category Comparison: Categories 01 and 04 significantly outperform others in terms of total sales.
Sales Channels:

Direct Sales: $199,516.90
Online Sales: $201,895.02
Wholesaler Sales: Showing steady growth, contributing to a substantial portion of overall sales.
Payment Modes:

Cash and Online payments are almost equally preferred, with a slight edge for online transactions.
Product Performance:

Top Selling Products: Product01, Product02, and Product05 have the highest sales figures.
Product Categories: Products in Category01 and Category04 are top contributors to overall sales.
Tools and Technologies
Excel: For data storage, manipulation, and initial analysis.

Impact
This project has significantly enhanced our ability to make data-driven decisions, optimized inventory management, and improved our understanding of customer preferences and behavior.

Data Accuracy: Leveraged VLOOKUP for precise data integration from the Master Data sheet.
Efficiency: Automated sales and cost calculations for real-time insights.
Dynamic Analysis: Utilized OFFSET for creating flexible data ranges.
Conditional Logic: Implemented conditional lookups to enhance data relevance.
Trend Analysis: Identifies sales trends over time to help forecast future sales and inventory needs.
Tools and Technologies
Excel: For data storage, manipulation, and initial analysis.


This project not only improved my proficiency in Excel but also demonstrated the power of advanced formulas in streamlining data analysis and reporting.
