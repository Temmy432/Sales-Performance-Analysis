# Sales-Performance-Analysis
A data analysis project using SQL and Power BI to uncover key sales trends, top-performing products, customer segments, and regional insights. Includes strategic recommendations to drive growth and optimize performance.

# 📊 Sales Performance Analysis Report (Oct 1, 2016 – Dec 1, 2019)

---

# ________________________________________
## INTRODUCTION
This report presents a comprehensive analysis of the company's sales performance from October 1, 2016, to December 1, 2019. It provides an in-depth review of revenue trends, sales growth, and key performance indicators across various products, locations, and sales channels. The report examines both external and internal factors that influenced performance during this period, identifying key opportunities and challenges. Data-driven insights and strategic recommendations are provided to enhance future sales performance and drive sustainable business growth.

# ________________________________________
## OBJECTIVES
• Identify Key Revenue Contributors: Determine the major drivers of overall sales based on customer type.  
• Yearly Performance Analysis: Evaluate sales performance on an annual basis.  
• Product Trend Comparison: Compare sales trends across different products over the years.  
• Geographical Impact: Identify the location with the highest sales contribution.  
• Brand Performance: Determine the brand with the highest sales volume.  
• Product Revenue Leader: Identify the product that generated the highest total sales.  
• Customer Segment Analysis: Assess which customer type produced the highest sales revenue.

# ________________________________________
## DATA SOURCE
The dataset encompasses comprehensive sales records from 2016 to 2019, detailing key variables such as Sales ID, Product ID, Customer Name, Location, Salesperson, Customer Type, Date, Quantity, and Total Sales. In addition, it includes a corresponding product record containing Product ID, Product Name, Brand, and Unit of Measure (UoM). This data was obtained through rigorous online research and serves as the foundation for our analysis.

# ________________________________________
## DATA OVERVIEW
The analysis is based on two datasets:

### Sales Record Dataset
• Dimensions:  
  o Rows: 12  
  o Columns: 9  
• Column Descriptions:  
1. Sales ID: A unique identifier for each individual sales transaction.  
2. Product ID: A reference to the specific product involved in the sale, linking to the product record.  
3. Customer Name: The name of the customer who made the purchase.  
4. Location: The geographical area where the sale occurred.  
5. Salesperson: The name or identifier of the individual who facilitated the sale.  
6. Customer Type: The category or classification of the customer (e.g., corporate, individual).  
7. Date: The date on which the transaction took place.  
8. Quantity: The number of product units sold in the transaction.  
9. Total Sales: The monetary value generated from the transaction.

### Product Record Dataset
• Dimensions:  
  o Rows: 4  
  o Columns: 4  
• Column Descriptions:  
1. Product ID: A unique identifier for each product, corresponding to the Product ID in the sales record.  
2. Product Name: The name or description of the product.  
3. Brand: The brand associated with the product.  
4. Unit of Measure (UoM): The measurement unit used for quantifying the product (e.g., piece, gram, liter).  
These datasets, obtained through rigorous online research, provide a robust foundation for analyzing sales performance and product trends over the period from 2016 to 2019.

# TOOLS USED
• SQL: Utilized for querying and manipulating the dataset, ensuring accurate data extraction, filtering, and transformation for analysis.  
• Power BI: Employed for data visualization, enabling clear representation of trends, patterns, and insights through interactive dashboards and reports.



![](Images/Screenshot%202025-04-22%20095233.png)



# ________________________________________
## KEY INSIGHTS
• Top-Contributing Customer Type:  
  o Restaurants generated the highest sales revenue, followed by hotels.  
  o Corporate and retail customers contributed significantly less.  

• Product Performance:  
  o "Viktory Ground 500 Gr" and "Illy Ground 250 Gr" achieved the highest sales values.  
  o "San Pellegrino Sparkling 500 Ml" recorded lower sales compared to other products.  
  o "Mango Puree Sorbetto" had no sales over the period.  

• Sales Trends Over Time:  
  o There was a sharp decline in sales from 2016 to 2017, followed by a gradual recovery in 2018 and 2019, although levels did not return to those observed in 2016.  

• Geographical Impact:  
Jakarta stands out as the top-performing location with a total sales contribution of 458 million, significantly surpassing all other regions. This indicates that Jakarta is a major revenue hub and should be a strategic focus for future sales and marketing efforts.

• Top-Contributing Customers:  
  o McDonald's (McD) emerged as the largest contributor, accounting for 41.97% of total sales.  
  o Other notable customers included Holiday Inn, Ritz Carlton, Grand Hyatt, Sate Senayan, and Microsoft.  

• Brand Performance by Quantity Sold:  
  o The "Viktory" brand led in terms of quantity sold, followed by the Water and Illy brands, albeit with significantly lower volumes.  

• Sales Distribution by Year and Product:  
  o "Illy Ground 250 Gr" maintained steady sales performance over the years.  
  o "San Pellegrino Sparkling 500 Ml" experienced a significant decline after 2016 before stabilizing.  
  o "Viktory Ground 500 Gr" also saw a sharp decline post-2016, with a partial recovery in subsequent years.  

• Sales Value Extremes:  
  o The highest recorded sales transaction was IDR 200M, while the lowest was IDR 18M.  
  o The total sales value over the period amounted to IDR 679M.  

• Sales Channel Analysis:  
  o Hotels and restaurants are critical sales channels, underscoring the importance of strong business-to-business (B2B) partnerships in driving revenue.  
  o Further channel-specific analysis may reveal additional opportunities to increase market share or refine product offerings.

# ________________________________________
## RECOMMENDATIONS
• Mango Puree Sorbetto:  
Reposition the Mango Puree Sorbetto, which recorded no sales between 2016 and 2019, by targeting markets with higher purchase potential. Consider marketing this product in school environments, where there is a greater likelihood of engaging a youthful customer base interested in ice cream.

• Strengthen Key Customer Relationships:  
Focus on enhancing engagement with the largest customer segments—primarily restaurants and hotels—by offering tailored promotions, loyalty programs, or bulk purchase discounts. Given that McDonald's (McD) is the top customer, strengthening this partnership should be a priority.

• Product Quantity and Brand Strategy:  
Since certain brands are achieving higher sales volumes but generating lower revenue, reassess pricing strategies to maximize profitability. Evaluate brands with lower sales to determine whether they should be repositioned, improved, or potentially discontinued.

• Optimize Pricing and Inventory Management:  
Utilize historical sales data to fine-tune pricing strategies, avoid overstocking of low-demand products, and ensure adequate supply of high-demand items.

• Target Market Expansion:  
Identify geographic areas and customer segments with growth potential and allocate resources accordingly to maximize market penetration and revenue growth.

• Revise Pricing and Discount Strategies:  
Reassess current pricing models, particularly in cases where increased sales volumes have not translated into proportional revenue growth. Implement targeted discounting or bundling strategies to improve margins while maintaining competitive pricing.

# ________________________________________
## CONCLUSION
In summary, the analysis of the sales data reveals several critical insights that inform the strategic direction of the company. While certain high-performing products and key customer segments are driving revenue, notable challenges include the decline in sales during specific periods and the underperformance of select product lines. These trends emphasize the need to optimize the product portfolio, revise pricing strategies, and strengthen strategic B2B partnerships.  
Additionally, Jakarta emerged as the top-performing location with a sales contribution of 458 million, significantly ahead of other regions. This highlights the geographical imbalance in sales performance and underscores the opportunity to replicate Jakarta’s success model in underperforming areas.  
By focusing on targeted market expansion and leveraging data-driven sales forecasting, the company is well-positioned to address these challenges and capitalize on emerging opportunities. Implementing the outlined recommendations will not only enhance operational efficiency but also support sustained growth and a stronger competitive market position.

---

