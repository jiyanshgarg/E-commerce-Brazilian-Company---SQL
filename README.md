# Case description

Welcome! This is a Brazilian ecommerce public dataset of orders made by a E-commerce company. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

This is real commercial data, it has been anonymised, and references to the companies and partners in the review text have been replaced with the names of Game of Thrones great houses.

# Context

This dataset was generously provided by E-commerce company, the largest department store in Brazilian marketplaces. E-commerce company connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the E-commerce company Store and ship them directly to the customers using E-commerce company logistics partners.

After a customer purchases the product from E-commerce company Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.

# Executive summary
This project establishes a data schema containing all the data in the E-commerce company set following the given structure of the publisher. The original data stored in separate csv files have been imported to separate tables in a schema with proper data type assigned to all variables. The project achieves the following points:

- Creating a schema to store data tables replicating the data structure given by the publisher of the E-commerce company data set
- Creating tables following a logical order so that all the connections among the tables are properly preserved
- Importing the data simultaneously with the table creations and adjusting the data when necessary
- Assigning suitable data types to the given data, which contain three main types: integer, numeric, text, and timestamp
- Checking the result by using the schema information table
- Constructing the entity relationship diagram for comparing the structure of the imported and the original databased
The data is now ready to be extracted and manipulated using SQL queries. The next steps might be exploratory analysis and data visualization so that more insights can be gained for further investigations.

## Tools ans Databases Used
- Google BigQuery

## Insights and Business Recommendations
- This dataset provides the information that the customers are placing orders 
from 27 states and 4119 cities, which shows that Brazilian E-commerce has established a 
significant presence across various regions in Brazil
- Early months 
show the rapid growth i.e. January 2017 with 79900% growth in the sales, which followed 
by further increase of 122.5% in February 2017 and sudden drop out of sales in 
September 2018 i.e. -99.75%.  The company should plan a strategic promotion and marketing scheme so that sales 
would not drop down by giving discounts to customers or adding combo stocks.
- The state SP dominates orders, 
maximum orders in August 2018 i.e. 3253, which consistently follow by the state 
RJ and MG but in lower volumes, while the states AC and AP have least orders (less than 
10 orders per month). Regional disparities show the stronger e-commerce adoption in the 
SP, RJ and MG can be due to economically developed states then AC and AP.
- January 2018 shows a growth of 705%, which is significantly higher than other months. 
We need to analyze this trend to identify its causes, allowing us to replicate similar sales 
methods in other months. Implementing budget planning and analyzing seasonal trends can help us achieve 
better cost control.
-  The data reveals significant regional variations in order values :- -> states with high average order prices like PB ($191 avg.) and RO ($166 avg.) showing 
premium potential—ideal for upselling strategies. And For High-volume states like SP and MG deliver scale but lower margins ($109-$120 avg.), 
suggesting opportunities for bulk discounts.  
- For low-performing states (RR, AP), targeted incentives like free shipping could boost 
adoption. Prioritize tailored pricing and promotions to maximize revenue across all regions 
while addressing local market dynamics.
- Analysing the freight value highlights different patterns and opportunities for 
optimization in our logistics department. States like RR and PB have the maximum freight 
value which can be due to remote location or bad developed infrastructure, in opposite 
states like SP and PR have minimum freight value which can be due to well developed 
infrastructure and  economically strong states or high scale operation. For remote regions, Brazilian E-commerce could partner with the local business and 
courier services for the freight cost reduction. Find better freight to reduce the freight value for the customers which results in more 
demand or orders from them.
- By watching this data, we can judge 
that credit cards are the most preferred payment options i.e. used for approx 75% while 
shopping which is followed by the UPI method, the second most popular payment 
method.
-  To optimize payment strategies and drive sales growth, the 
e-commerce company should focus on promoting mid-range installment plans (2-6 
installments) by offering low or zero interest rates, as these are popular among customers 
and can attract budget-conscious shoppers. Simultaneously, the checkout process for 
single-payment buyers—who represent the majority (49060 orders)—should be 
streamlined with incentives like instant discounts to encourage faster conversions.
