# POWER-BI-PROJECT

# Table of Contents

1. [Project Background](#project-background)
2. [Project Deliverables](#project-deliverables)
3. [Data Columns Explanation](#data-columns-explanation)
4. [Financial Context](#financial-context)
5. [Significance of Financial Analysis](#significance-of-financial-analysis)
6. [Business Context](#business-context)
7. [Objectives](#objectives)
8. [Key Calculations](#key-calculations)
9. [Methodology](#methodology)
10. [Key Findings](#key-findings)
11. [Recommendations](#recommendations)
12. [Conclusion](#conclusion)
13. [Data Visualization](#data-visualization)




# Project Background

This Power BI project is dedicated to conducting a comprehensive financial performance analysis of the Office Supply dataset. The dataset serves as a valuable source of information, capturing intricate details related to the sales of office supplies. Our focus is on deriving meaningful financial insights to support strategic decision-making and enhance overall business profitability. Dataset was downloaded from [https://kaggle.com] 

### Project Deliverables

In addition to the Power BI dashboard and detailed analysis, this project includes a PowerPoint presentation summarizing key findings, insights, and recommendations. The presentation serves as a concise overview for stakeholders who may prefer a visual and narrative summary of the financial analysis.

...


### Dataset Columns Explanation

1. ### order_id:

 Data Type: Unique Identifier (Alphanumeric).
   
 Explanation: The order_id column serves as a unique identifier for each order in the dataset. It is an alphanumeric code 
    assigned to distinguish and track individual orders.

2. ### order_date:

Data Type: Date

Explanation: This column records the date when each order was placed. It provides a timestamp for when customers initiated their orders.

3. ### ship_date:

Data Type: Date

Explanation: The ship_date column indicates the date when each order was shipped, marking the moment when the products were dispatched for delivery.

4. ### ship_mode:

Data Type: Categorical

Explanation: This categorical column defines the shipping mode chosen for each order, representing how the products are transported to the customer. Examples of shipping modes could include standard shipping, express delivery, etc.

5. ### customer_name:

Data Type: Text (Alphanumeric)

Explanation: The customer_name column contains the names of customers who placed the orders. It serves to identify the individuals responsible for the orders.

6. ### segment:

Data Type: Categorical

Explanation: This categorical column classifies customers into different segments such as consumer, corporate, or home office. It helps categorize customers based on their characteristics and needs.

7. ### state:

Data Type: Categorical

Explanation: The state column indicates the geographical location or state where each order is placed. It is valuable for analyzing regional trends and understanding variations in customer behavior.
       



### Financial Context

In the fast-paced and competitive market for office supplies, understanding the financial dynamics is crucial for sustained success. This analysis aims to delve into various facets of financial performance, including revenue generation, profit margins, and the impact of discounting strategies. By leveraging the capabilities of Power BI, we intend to transform raw data into actionable intelligence that provides a clear picture of the financial health of the office supply business.

### Significance of Financial Analysis

1. #### Profitability Assessment: Evaluate the overall profitability of the business by examining key financial metrics such as Gross Sales, Revenue, and Profit.

2. #### Discounting Impact: Assess the effectiveness of different discount bands in driving sales and their influence on overall revenue and profit margins.

3. #### Cost and Revenue Dynamics: Understand the relationship between manufacturing costs, sales prices, and revenue to optimize cost structures and maximize profits.

4. #### Temporal Trends: Identify temporal trends to recognize patterns, seasonality, and potential opportunities for revenue growth.


### Business Context

This analysis is critical for stakeholders involved in shaping pricing strategies, discounting policies, and overall financial planning. By gaining a deep understanding of financial performance, decision-makers can formulate strategies that align with market dynamics, ensuring sustainable growth and competitive advantage in the office supply sector.

### Objectives

- Quantify Financial Metrics:  Calculate key financial metrics such as Gross Sales, Revenue, Profit, and Profit Margin to provide a comprehensive overview of the financial landscape.

- Evaluate Discount Strategies: Analyze the impact of different discount bands on sales, revenue, and profitability, enabling data-driven decisions on discounting policies.

- Optimize Cost Structures: Examine the relationship between manufacturing costs, sales prices, and profit margins to identify opportunities for cost optimization.

- Identify Business Trends: Explore temporal trends to unveil patterns and insights that can guide strategic decision-making for future growth.


Through these objectives, we aim to empower stakeholders with actionable insights that contribute to informed decision-making, ultimately enhancing the financial performance of the office supply business.

### Key Calculation

The project involves implementing various calculations, including:

- Calculation of the Discount Rate based on the Discount Band.
- Derivation of Gross Sales, Discount, Revenue, Manufacturing Cost, Profit Before Tax, Tax, Profit, and Profit Margin using provided formulas.

| Metric                  | Formula                                           |
|-------------------------|---------------------------------------------------|
| Gross Sales             | SUM('Units Sold' * 'Sale Price')                  |
| Discount                | Gross Sales * 'Discount Band'                     |
| Revenue                 | Gross Sales - Discount                            |
| Profit Before Tax       | Revenue - (Units Sold * 'Manufacturing Price')    |
| Profit Margin           | (Profit Before Tax / Revenue) * 100              |
| Tax on Profit           | Profit Before Tax * 0.05                          |
| Profit After Tax        | Profit Before Tax - Tax on Profit                 |

These were calculated using the DAX formular on Power BI.


### Methodology

This project employs Power BI for data visualization, taking advantage of its robust capabilities for creating interactive dashboards and reports. The dataset undergoes data cleansing, transformation, and the application of calculations within Power BI to ensure accurate and insightful results.


### Key Findings.

1. #### Oyo State Revenue and Profitability Discrepancy:

Despite contributing the most to total revenue, Oyo State lacks profitability proportionate to its sales. This suggests a potential issue with the product mix in Oyo, where certain items may not align with high-profit margins. Further exploration is needed to identify specific products or categories causing this imbalance.

2. #### A4 Paper Sales Surge in December 2014:

A substantial increase in A4 paper sales during December 2014 indicates a notable market demand for this product. Understanding the factors behind this surge can provide valuable insights for successful strategies that can be applied to other products or periods. It's essential to investigate what contributed to the increased demand and replicate successful elements.



3. #### Revenue Drivers: Biro, Notepad, and Markers:

Biro, Notepad, and Markers emerge as pivotal revenue drivers, showcasing their popularity and market demand. A strategic focus on these items can further optimize sales and marketing efforts. Understanding consumer preferences for these products can lead to targeted marketing strategies to enhance their market presence.

4. #### Revenue Drivers: Biro, Notepad, and Markers:

Biro, Notepad, and Markers emerge as pivotal revenue drivers, showcasing their popularity and market demand. A strategic focus on these items can further optimize sales and marketing efforts. Understanding consumer preferences for these products can lead to targeted marketing strategies to enhance their market presence.

5. #### Revenue Increase in 2014:

There was a substantial increase in revenue in 2014 compared to 2013. The revenue in 2013 was 27 million Naira, while in 2014, it surged to 94 million Naira. This significant growth indicates positive market dynamics or successful business strategies implemented during 2014.

### Recommendations

1. #### Leverage A4 Paper Success:

 Capitalize on the success of A4 paper sales by investigating and replicating the strategies that contributed to the surge in December 2014.

2. #### Strategic Focus on Key Revenue Drivers:

 Direct strategic efforts towards Biro, Notepad, and Markers, leveraging their popularity to optimize marketing, inventory management, and potential bundling promotions.

3. #### Segment-Specific Strategies:
 
 Develop segment-specific strategies to address the revenue gap between segments, tailoring marketing and product offerings to the unique needs and preferences of each segment.

4. #### Expand Success in Small Business Segment:

 Understand the factors driving profitability in the Small Business segment and explore ways to replicate this success in other segments, fostering a balanced and lucrative business model.

5. #### Promote Cross-Selling and Bundling:

Encourage cross-selling and bundling promotions, especially with high-demand items like Biro, Notepad, and Markers. Offering discounts or promotions for purchasing these items together can boost overall sales and increase the average transaction value.

6. #### Collaborate with Small Business Customers:

Engage with Small Business customers to understand their needs and preferences better. Establishing strong relationships with this segment can lead to valuable feedback, which can be used to tailor products, services, and promotions to their specific requirements.

7. #### Explore Online Sales Channels:

Explore opportunities to expand sales channels through online platforms. This can provide access to a broader customer base, improve convenience for customers, and open new avenues for revenue growth. 

By incorporating these recommendations, you can further refine your strategies to capitalize on successful product lines, address segment-specific challenges, and sustain long-term business growth. These recommendations are designed to guide the business towards sustainable growth, enhanced profitability, and improved customer satisfaction. Continuous monitoring, adaptation, and strategic implementation will be crucial for the successful execution of these strategies.

### Conclusion

In conclusion, our analysis has peeled back layers of insight into the intricacies of product performance, revenue distribution, and segment profitability within our business landscape. The examination of Oyo State's contribution, the surge in A4 paper sales, and the disparities across segments has unearthed critical aspects of our market dynamics.
The prominence of Biro, Notepad, and Markers as revenue drivers and the profitability of the Small Business segment underscore significant areas of strength within our operations. It is evident that these elements play a pivotal role in shaping our financial landscape.
Moreover, the positive trend in profitability from 2013 to 2014 signifies an encouraging trajectory for our business. However, challenges, particularly in aligning profitability with sales in Oyo State and addressing revenue imbalances across segments, demand strategic attention.
By delving into these nuances, we are better equipped to navigate the complex terrain of our market. The imperative now lies in implementing judicious strategies that capitalize on our strengths, address challenges, and chart a course for sustained growth and market responsiveness.
This synthesis of findings not only provides us with a comprehensive understanding of our current standing but also serves as a compass for steering our business towards a future of enhanced performance and profitability.



### Data visualization

<img width="638" alt="Screenshot 2024-01-23 061621" src="https://github.com/Richieprizie/POWER-BI-PROJECT/assets/141673351/8cf06339-1b82-48e3-bf31-7408c5e25ddf">


























