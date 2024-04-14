# COFFEE SHOP SALES ANALYSIS
## OVERVIEW
This dataset contains the 6months sales data of a XYZ coffee shop in the year 2023. The data covers a range of variations in sales distribution, transaction history, trends and patterns, as well as geographical and customer segmentation of the coffee shop sales in the given period. 

## AIM
The aim of analyzing this data is to extract actionable insights and valuable information that can be used to improve various aspects of coffee shop sales operations and strategy. 
The primary aim is to optimize sales performance by identifying trends, patterns and factors influencing product sales to gain deeper understanding of customer preferences, behavior and needs.

## OBJECTIVE
The objective of this analysis is to gain insights that can inform strategic decisions aimed at optimizing sales performance and maximizing revenue. Here are some specific objectives:
1.	Identify Trends: Understanding the overall trends in product sales over time.
2.	Optimize Product Mix: Determining which types of products are most popular among customers and adjust the product mix accordingly to meet demand.
3.	Sales Distribution: Breaking down sales by different categories such as product category (coffee, tea, bakery), size (large, small, regular) and product type (barista espresso, gourmet brewed coffee, drip coffee)

## DATASET INTRODUCTION
This dataset contains the sales data of a coffee shop. It has 149,116 rows and 19 columns
It contains the transaction id of every customer and their order description.
### COLUMN DESCRIPTION
> - transaction_id: The unique id of the transactions
> - transaction_date: The date of the transactions
> - transaction_time: The time of the transaction
> - store_id: The id of the store as there are multiple stores in a city or country
> - store_location: The location of the store
> - product_id: The product id as there are multiple products like coffee, tea, bakery, etc.
> - transaction_qty: The quantity of that order
> - unit_price: The price of that unit
> - Total_Bill: Total bill, it is transaction_qty*unit_price
> - product_type: The type of product for each category like Coffee (barista espresso, gourmet brewed coffee), bakery (Pastry), etc.
> - product_detail: The description of the product.
> - Size: The size of the product like large, small, regular
> - Month Name: The name of the month of the transaction
> - Day Name: The name of the day of the week of the transaction
> - Hour: The hour of the transaction
> - Month: The month of the transaction
> - Day of the Week: The day of the week of the transaction

## RESEARCH QUESTIONS
1.	What is the total sales generated at the coffee shop in the given period? 
2.  What is the overall sales trend for the coffee shop over the past months? Are sales increasing, decreasing or remaining stable?
3.	Which product category are most popular among the customers? 
4.	Which is the top-selling coffee drinks at the coffee shop?
5.  What size of coffee has the highest percentage of quantity sold.
6.	What is the average transaction value per customer?
7.	What are the busiest days and times for the coffee shop? How do sales vary throughout the day and week?
8.	How do sales vary between different store locations?
9.	Are there any notable difference in sales between weekdays and weekends?  

## METHODOLOGY
1.	Data Collection: The dataset was downloaded from Kaggle. Here is the link:  https://www.kaggle.com/datasets/divu2001/coffee-shop-sales-analysis
2.	Data Transformation: The data was loaded into power bi. Then, it was taken to power query editor on power bi for cleaning and transformation.
3.	Descriptive Analysis: Carried out data exploration that involves summarizing and describing the primary properties of the dataset.
4.  Exploratory Data Analysis (EDA):  Conducting EDA to understand the basic characteristics of the data, such as distribution of sales, and trends over time.
5.  Data Visualization: Visualization techniques like bar chart, column chart, pie chart and line graphs were used.
6.  Data Analytics Tool: **Power Bi** was used for the analysis.
7.	Hypothesis Formulation: Based on the EDA, research questions were formulated to investigate further.
8.	Segmentation: The data was segmented based on product category, product type, size, and store locations.
9.	Interpretation and Reporting: Actionable insights were derived from the analysis by interpreting results of the visualizations.
10.	Recommendations: Based on the analysis, recommendations for strategies to improve the coffee shop sales were made.

## DATA VISUALIZATION
Ribbon Chart, Bar chart, Pie chart, Doughnut chart, Card, Table and Area chart were used for the visualizations.

## INSIGTHS
> - The total sales generated in the coffee shop sales data is $698,496.
> - The average transaction value per customer for the coffee shop for the specified period is 4.68.
> - Sales in the coffee shop has constantly been increasing after it experienced a decline in the second month, February.  Therefore, the highest sales of $166,439 was made in June. 
> - The most popular product among customers at the coffee shop is **Coffee** and the top selling product type for coffee is **Barista Espresso**.
> - The **_regular size_** of Barista Espresso coffee is the highest sold coffee product and product category generally in terms of quantity.
> - The peak day and time of sales for the coffee shop is Tuesday, from 8am to 10am respectively.
> - More sales are made during weekdays compared to weekends.
> - **Hell’s Kitchen** is the store location that contributes the highest revenue of $90,754 to the business.

## RECOMMENDATIONS
The XYZ sales and marketing department should consider implementing the following practices:
> - Promoting popular products such as coffee and optimize pricing strategies for higher-margin products.
> - Ensuring optimal customer service during peak sales periods.
> - Offering special promotions or incentives during slower hours to attract more customers.
> - Personalize marketing efforts and rewards to enhance customer engagement and loyalty.
> - Compare sales performance with competitors to identify area of improvements and capitalize opportunities
> - Analyze pricing strategies, product offerings, and customer service to differentiate the coffee shop from competitors

## CONCLUSIONS
* This analysis identifies the key sales drivers and opportunities for targeted marketing and operational enhancements to drive growth and customer satisfaction.

