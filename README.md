# Yelp-sentiment-anaylsis
Yelp is currently the most widely known forum in the US that helps customers find great restaurants and merchants. Meanwhile, it can also help business owners improve their service by reviewing what customers comment or rate. However, the data on yelp has never been fully used. Massive data such as reviews, business information, rates given by users and contain metadata are sometimes undervalued by both business owners or app users. In this project, we will dig deeper into this data to get more valuable information behind them.
This project focus on business information attributes with all kinds of online reviews of the business. The purpose of this project is to fetch yelp dataset into an appropriate database and utilize the data with several models to:
1. Find out crucial attributes that lead to the success of a business
2. Analyze the sentiment of the reviews
3. Visualize the data to help make better decisions on the business 
4. Get ourselves more familiar with how to build a data product from beginning to end.

The dataset is from Yelp open dataset: https://www.yelp.com/dataset/download
There are 6 different json files in the zip package, but only 2 of them are needed for sentimental analysis:
‘Business.json’, which contains all the information about the business including name, address, attributes, and categories.
“Review.json”, which contains both review text and the stars the user game with the user_id that wrote the review and the business_id the review is written for.
