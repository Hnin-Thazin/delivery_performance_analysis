# delivery_performance_analysis

Tools and skills( Power BI)
Data Cleaning and transforming using Power Query
Data Modeling using star schema 
DAX measures for average and rate calculations 
Business Insights and data visualization
Key Insights
1. Geographic Outliers : While our average delivery day is 12 days, Santa Cruz De Goias is experiencing a massive lead time of 125 days. This single city is approximately 10x slower than our average. 
We will need to do a carrier audit for Top 10 slowest cities, to examine if these delays are due to distance or regional warehouse inefficiencies.
2.Promise Error Surprise: We are delivering 8-21 days faster than the day we show our customers. A 21 days gap in states like AC is showing our estimate logics is over calculating which can lead to cart abandonment from customers thinking shipping will take too long 
I recommend to decrease the promise window by 5 days and monitor On-time delivery rate again.
3.Delivery speed actually improved during peak order of August which indicates that our warehouse and carrier handle high order volume efficiently
4.Sao Paulo and Rio De Janeiro are having the highest shipping cost but they are not in the top 10 slowest cities. This confirms that our high-cost areas are performing at an acceptable speed
I recommend to make a offer of volume-based discounts to cover shipping cost
5.Administrative funciton is at a high-level performance as it is below 0.6 hour despite only a distinct delay in April. This shows almost 97% of the delivery cycle is weighting on logistics.
This project helped me advance with my DAX formulas and analytical thinking skill to translate raw data into actionable business insights.
