# MAVEN ROASTERS SALES ANALYSIS

An Excel project that aims to provide Maven Roasters, a fictitious coffee shop operating across three locations in New York City, with actionable insights. These insights are intended to inform strategic decisions and optimize Maven Roasters' overall operational effectiveness

## Table of Content
- [Project Overview](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#project-overview)
- [Project Scope](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#project-scope)
- [Buisness Objective](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#business-objective)
- [Document Purpose](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#document-purpose)
- [Use Case](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#use-case)
- [Data Source](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#data-source)
- [Data Cleaning and Processing](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#data-cleaning-and-processing)
- [Data Analysis](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#data-analysis-and-insight)
- [Data Visualization](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#data-visualization)
- [Recommendation](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#recommendation)
- [Conclusion](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis#conclusion)

## Project Overview

Maven Roasters, a fictitious coffee shop operating across three locations in New York City, has accumulated transaction records containing valuable information about their sales. This project aims to analyze these transaction records to gain insights into Maven Roasters' sales trends, busiest days, product popularity, and revenue contributions. 

## Project Scope

This project involves an in-depth analysis of Maven Roasters' sales data, encompassing key elements such as transaction date, timestamp, location, and detailed product-level information. The analytical scope spans historical data from January 1, 2023, to June 30, 2023, providing a comprehensive view of Maven Roasters' operational performance during this period. The analysis was conducted across all three Maven Roasters locations situated within New York City, aiming to capture a holistic understanding of the coffee shop's sales dynamics and trends across diverse locations within the specified timeframe.

## Business Objective

The overarching goals of this analysis are multifaceted, aiming to provide a nuanced understanding of Maven Roasters' sales performance. These objectives encompass unraveling the trends in Maven Roasters' sales over a specified period, discerning the busiest days of the week while delving into the factors that influence these patterns, scrutinizing product-level data to identify both the best-selling and least-selling items, and ultimately quantifying the unique revenue contributions of each product to the broader success of the business. Through a comprehensive exploration of these aspects, the analysis aspires to furnish actionable insights that can inform strategic decisions and optimize Maven Roasters' overall operational effectiveness.

## Document Purpose

This documentation serves as a guide for project stakeholders, providing insights into the project's objectives, data sources, data analysis, visualizations, and any other relevant information

## Use Case

Several stakeholders within and outside the organization can benefit from the Maven Roasters Sales Analysis. These stakeholders include:

**1. Management Team**

- **Key Decision Makers:** Executives and top-level managers can leverage the analysis to make informed decisions regarding sales strategies, resource allocation, and overall business direction.
- **Operational Managers:** Managers overseeing day-to-day operations can use insights to optimize staffing, inventory management, and promotional activities.

**2. Marketing Team**

- **Marketing Managers:** By understanding sales trends and product popularity, the marketing team can tailor campaigns to boost sales, promote popular products, and maximize revenue.
- **Promotions Team:** Insights into busiest days and customer preferences can inform the timing and content of promotional activities.

**3. Sales Team**
- **Sales Representatives:** Front-line sales staff can benefit from understanding which products are most popular, enabling them to make informed recommendations to customers.
Customer Service Team
- **Customer Support Representatives:** Awareness of busy days and popular products allows customer service teams to anticipate and address customer inquiries or concerns more effectively.

## Data Source

This project employs dataset, sourced from the [Maven Analytics](https://www.mavenanalytics.io/data-playground?page=3&pageSize=5) website, designed specifically for practice purposes. The dataset, presented in the form of an Excel file, is a singular table boasting an expansive 149,116 rows and 11 columns. Within this structured framework, a wealth of information characterizes Maven Roasters' sales data, providing a nuanced understanding of various facets of their business operations.

The dataset encompasses key attributes essential for a comprehensive analysis, including Transaction ID, Transaction Date, Transaction Time, Transaction Qty, Store ID, Store Location, Product ID, Unit Price, Product Category, Product Type, and Product Detail. Each of these variables contributes crucial insights, collectively painting a vivid portrayal of Maven Roasters' transactional scenario.

## Data Cleaning and Processing

Having clean data for analysis is crucial because it ensures that the insights derived from the analysis are accurate, reliable, and free from biases introduced by data issues. Clean data facilitates a smoother analytical process, enabling researchers, analysts, and decision-makers to draw meaningful conclusions and make informed decisions based on trustworthy information.

After conducting a thorough assessment and examination of the data to ascertain its quality and suitability for this analysis, and meticulously evaluating the overall data quality by checking for errors, inconsistencies, missing values, and duplicate entries, it has been observed that the dataset for this analysis is well-structured, consistent, and devoid of significant issues that could impede analysis or interpretation. The data adheres to a standardized format and consistent naming conventions. All necessary data fields are present and also diligently populated. The data values are accurate, and appropriate data types have been assigned to each column. Importantly, the dataset contains no duplicate records. Therefore, based on this comprehensive evaluation, it is conclusively determined that no cleaning is required, as the dataset is inherently well-prepared and ready for meaningful analysis, ensuring accuracy, reliability, and trustworthiness in the insights derived from the data.

The following process was also carried out on Maven Roasters’ Sales data during data processing.

- Added New Columns 

New columns, namely Year, Month, and Week, were incorporated into the Maven Roasters’ Sales data. These additional columns play a pivotal role in the analysis by facilitating an exploration of how Maven Roasters' sales have trended over time. Furthermore, they contribute significantly to understanding which days of the week tend to be the busiest, with the aim of unraveling the factors that influence these patterns. The inclusion of these temporal indicators enhances the analytical capabilities of the dataset, allowing for a more comprehensive assessment of sales dynamics and patterns over different timeframes.

Then, the dataset was imported into Excel Power Pivot for further analysis.

## Data Analysis and Insight

The primary aim of this analysis is to derive valuable insights from Maven Roasters' sales data by conducting a comprehensive examination of key factors. This multifaceted exploration involves several pivotal objectives. Firstly, it seeks to comprehend the temporal trends in Maven Roasters' sales over time, entailing the identification of patterns within the sales data. Secondly, the analysis aims to identify the days of the week consistently experiencing peak activity for Maven Roasters, probing into the underlying factors influencing transaction volumes on specific days. Thirdly, a detailed investigation into the dynamics at the product level is undertaken, discerning the most and least frequently sold products, and determining the individual revenue contribution of each product to the overall business.

As a result, this analysis provides insights addressing the following questions.

**1. How have Maven Roasters sales trended over time?**

The question inquiries into the historical patterns and changes in the sales performance of Maven Roasters, a coffee shop. It seeks to understand the overall trajectory of Maven Roasters' sales, uncovering whether sales have been consistently increasing, decreasing, or exhibiting fluctuations. This analysis helps in identifying periods of growth, potential seasonality, or any patterns that might impact future decision-making and strategic planning for the coffee shop.

To address this question, in Microsoft Excel Power Pivot, a comprehensive measure was developed to calculate the total revenue made by Maven Roasters for each month using DAX (Data Analytics Expression) Code. This measure was designed to analyze the sales data, 
aggregate it on a monthly basis, and provide a clear and detailed summary of the total revenue achieved by Maven Roasters in each respective month. The insights derived from this calculation serve to identify patterns, changes, and trends in the sales performance over time.

*DAX code for calculating Total Revenue*

```Total Revenue = SUMX(Maven_Data, Maven_Data[unit_price]*[transaction_qty])```

This measure was then incorporated into the visualization process using a line chart. Line charts serve to visually represent and analyze the dynamic patterns and fluctuations in sales data, offering a clearer and more insightful understanding of the temporal dynamics within the dataset.

![](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis/blob/main/Revenue_Trends.png)

From the above analysis,
- The total revenue shows a consistent increase from January to June, indicating a positive trend in sales over the six-month period.
- There is noticeable growth in revenue during the March to June, suggesting potential seasonal influences or increased customer activity during this period.
- June stands out as the month with the highest revenue, indicating heightened sales activities or successful promotions during that period.

After the initial analysis, I dug deeper to figure out which months had higher or lower revenue compared to the previous month. This detailed exploration helped to understand the patterns in revenue changes over time. The results of this analysis are neatly shown in a waterfall chart, making it easy to see and grasp the factors influencing revenue fluctuations from month to month.

A comprehensive approach was taken to create a measure in Excel Power Pivot that calculate percentage increase in revenue compared to the previous month using DAX (Data Analytics Expression) Code

*1. DAX code for calculating Total Revenue*

```Total Revenue = SUMX(Maven_Data, Maven_Data[unit_price]*[transaction_qty])```

*2. DAX code for calculating Previous Month Sales* 

```Previous Month Revenue = CALCULATE([Total Revenue], PREVIOUSMONTH('Calendar'[Date]))```

*3. DAX code for calculating % Increase in Sales Compared to Previous Month*

```% Changes in Revenue = DIVIDE([Total Revenue] - [Revenue Previous Month], [Revenue Previous Month],0)```

Then, the ‘% changes in revenue’ measure was subsequently employed in conjunction with a visualization tool, a waterfall chart

![](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis/blob/main/Monthly_Revenue.png)

- The first notable observation is a decrease in revenue in February, signifying a 6.77% reduction compared to January. This decline could be due to various factors, such as seasonal trends or specific business conditions during that period.
- March and April demonstrate substantial positive growth, with a 29.80% increase from February to March and a further 20.34% increase from March to April. These months may have witnessed successful initiatives or favorable market conditions contributing to revenue growth.
- The positive trend continues into May, with a 31.77% increase compared to April. This sustained growth suggests ongoing success or effective strategies implemented by the business during this period.
- While June still shows growth at 6.23% compared to May, the rate of increase is more moderate. This might indicate a stabilization or a slight slowdown in revenue growth compared to the preceding months.

**2. Which days of the week tend to be busiest, and why do you think that's the case?**

This involve analyzing the sales data to determine on which days of the week the coffee shop, Maven Roasters, experiences higher levels of business activity, and to provide insights into the potential reasons behind these patterns. To provide answer to this question, it's essential to identify busiest day of the week based on a certain criterial. 

The determination of the busiest day of the week in this analysis was based on a meticulous examination of Maven Roasters' sales data. The process involved aggregating sales data by day of the week and subsequently calculating the total revenue generated on each specific day. By identifying the day with the highest revenue contribution to the overall revenue generated during the analyzed period, we pinpointed the busiest day of the week.

By emphasizing revenue as the determining factor for busyness, the analysis goes beyond transaction volume alone, capturing the overall financial significance of each day of the week. This approach provides valuable insights for business strategy, useful for understanding the financial impact of business activity on different days and helping Maven Roasters optimize operations and tailor marketing efforts to capitalize on the most lucrative days.

To answer the question, the analysis entailed the creation of a measure to calculate the total revenue generated on each day. This involved summing the sales amounts of all transactions occurring on the respective days, providing a quantitative measure of the financial impact for each day. Following this, the transaction records were systematically grouped and organized based on the day of the week, facilitated by a visualization tool, specifically a column chart. This chart offered a clear and visual representation of sales activities on each specific day. By pinpointing the day with the highest total revenue, we successfully determined the busiest day of the week through a comprehensive analysis grounded in revenue data.

*DAX code for calculating Total Revenue*

```Total Revenue = SUMX(Maven_Data, Maven_Data[unit_price]*[transaction_qty])```

![](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis/blob/main/Busiest_Week.png)

Based on the provided total revenue data for each day of the week, the busiest weekday in terms of revenue generated appears to be Monday. Monday has the highest total revenue among all weekdays, with $101,677. This indicates that Monday is the busiest day for the business in terms of sales.

Here are some potential insights into why Monday might be the busiest day.

-	Businesses may strategically launch promotions, discounts, or special offers on Mondays to attract more customers and stimulate sales at the beginning of the week.
-	If new products are released or special events are hosted on Mondays, it could drive increased customer traffic and spending.
-	For businesses closely tied to salary cycles, Monday could align with payday for certain groups of customers, leading to increased disposable income for spending.
-	The location of the business and surrounding activities in the area, such as community events or local attractions, could contribute to increased foot traffic on Mondays.
-	Consumer behavior often follows routines. If Mondays are traditionally associated with shopping or dining out, it could contribute to a consistent pattern of higher revenue on this day.

After the initial analysis, I extended the examination to determine if the busiest day is consistent across store locations or if it varies. Employing the same approach, a line chart was utilized to identify revenue trends for each day across different store locations. This visualization effectively highlighted the data, allowing for the identification of the busiest day in each location.

![](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis/blob/main/Revenu_Across.png)

In analyzing the provided revenue data across store locations, the busiest weekday appears to vary across the different locations.

- Wednesday generates the highest revenue in Astoria, indicating it's the peak day for customer engagement and sales.
- Hell's Kitchen experiences peak revenue on Tuesday, suggesting this day is particularly lucrative and busiest for the store.
- Lower Manhattan sees the highest revenue on Monday, showcasing specific day with heightened customer activity.

**3. Which products are sold most and least often? Which drive the most revenue for the business?**

This question aims to understand the popularity and financial impact of different products on the coffee shop's overall performance. By identifying top-selling products, least-selling products, and those driving the most revenue, the business can make informed decisions about inventory management, marketing strategies, and potentially introduce promotions or adjustments to product offerings.

The determination of the top and least selling products was based on analyzing sales data to identify items that customers frequently purchase in higher quantities or sold less frequently. In Excel Power Pivot, a measure was created to calculate the total quantity sold for each product. Subsequently, a bar chart was employed as a visualization tool to display the results. To enhance clarity and focus on significant insights, the filter pane was employed to display only the top 5 best-selling products and the least 5 selling products, determined by quantity sold.

A comprehensive approach was taken to create a measure that calculate total quantity sold.

*DAX code for calculating Total Quantity*

```Total Quantity Sold = SUM(Maven_Data[transaction_qty])```

**Top 5 Selling Product**
![](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis/blob/main/Top_5.png)

- With the highest quantity sold (4708 units), Earl Grey Rg leading in quantity sold, this product holds a prominent position, suggesting it's a customer favorite and potentially a key revenue driver.
- Dark Chocolate Lg, Latte, Morning Sunrise Chai Rg, and Peppermint Rg products have relatively high quantities sold, suggesting consistent demand across the board. These products, while not the top-sellers, maintain substantial quantities sold, indicating consistent popularity and contributing significantly to overall sales.

**Least 5 Selling Product**
![](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis/blob/main/Least_5.png)

- With the lowest quantity sold (118 units), Dark chocolate stands out as the least performing product in terms of sales.
- Jamacian Coffee River, Earl Grey, Guatemalan Sustainably Grown, and Spicy Eye Opener Chai products also exhibit lower quantities sold, indicating a lower level of demand compared to other items.

**Best Selling Product by Revenue**

This determination is based on identifying products that significantly contribute to the overall revenue of the business. The analysis encompasses not only transaction frequency but also considers the interplay of product price and the total sales amount for each item, providing a comprehensive understanding of the key revenue drivers

To identify the best-selling product by revenue in Excel Power Pivot, a dedicated measure was formulated to calculate the total revenue generated by each product. This measure was then utilized in conjunction with a bar chart, serving as a visual representation of the results. In order to streamline the presentation and emphasize key insights, the filter pane was employed to exclusively showcase the top 5 best-selling products, determined by the quantity sold. This approach ensures a clear and focused view of product performance based on revenue, facilitating strategic decision-making and actionable insights.

*DAX code for calculating Total Revenue*

```Total Revenue = SUMX(Maven_Data, Maven_Data[unit_price]*[transaction_qty])```

![](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis/blob/main/Top_Revenue.png)

- Sustainably Grown Organic Lg and Dark Chocolate Lg products stand out as the top revenue generators, with Sustainably Grown Organic Lg slightly leading in total revenue at $21,152.
- Latte Rg, Cappuccino Lg, and Morning Sunrise Chai Lg, while not the top revenue contributors, these products still exhibit substantial revenue figures, indicating consistent popularity among customers.

## Data Visualization

This data visualization was created using Microsoft Excel, each visual created displays information for each question in the business objective.

![](https://github.com/OchukoEjemudaro/Maven-Roasters-Sales-Analysis/blob/main/Dashboard.png)

## Recommendation
	
- Identify the specific initiatives or conditions that led to substantial growth in March and April. Consider replicating successful strategies, marketing campaigns, or operational improvements that contributed to this positive trend.
- Given the strong growth in May, there appears to be positive momentum. Maintain a focus on strategies that have been successful, and consider additional efforts to sustain or accelerate this growth.
- Gather feedback from customers during periods of growth and decline. Understanding customer preferences, needs, and concerns can provide valuable insights for tailoring products or services to meet market demands effectively.
- Foster collaboration among different departments within the organization. Cross-functional teams can provide a holistic perspective on factors influencing revenue, leading to more comprehensive and effective strategies.
- Earl Grey Rg should be promoted as a flagship product. Consider creating special promotions, combo deals, or marketing campaigns to further boost its visibility and sales.
- Adjust inventory levels for all products based on their respective quantities sold. Ensure sufficient stock for top-selling items while minimizing excess inventory for products with lower demand.
- Assess the pricing strategy for the least selling product. If pricing is a factor in higher sales, consider adjusting prices to align with customer expectations while maintaining profitability.
- Implement customer surveys to gather specific feedback on underperforming products. Understand customer preferences and areas for improvement.
- Develop targeted marketing campaigns to promote these top revenue-generating products. Highlight their unique features and appeal to maximize visibility.

## Conclusion

Incorporating these findings into Maven Roasters' strategic decision-making processes will enable the business to capitalize on its strengths, address areas for improvement, and maintain a customer-centric approach for sustained success in the coffee market. 

Thank You For Reading.

---

I’m interested in a Data Analyst role in an organization where I can showcase my skills, take more responsibilities, continue to learn, an organization that I can grow with, where my work will be highly beneficial to the organization.

You can reach me on ochukoejemudaro@gmail.com or [Twitter](https://twitter.com/iamochuks/) or [LinkedIn](https://www.linkedin.com/in/ochukoejemudaro01/)

THANK YOU

