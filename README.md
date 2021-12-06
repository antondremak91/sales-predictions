This project contains data analisys and item sales prediction in various stores. This should help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.
Here is the dictionary for the dataset:
![data_dictionary](https://user-images.githubusercontent.com/71296922/144911600-3cdecd4c-92f5-4a61-bc3e-75f3ba0d2a61.png)

On the first visualization we can see a correlation in data, that shows what features have the most impact on sales.
![heatmap_sales_preds](https://user-images.githubusercontent.com/71296922/144912379-8db01d12-aa3b-4974-95a0-74061dd79e15.png)
Visualization above shows that Item Max Retail Price has high impact on Outlet Sales.

Lets see what are the most popular products in each retailer size.
![sales_graph](https://user-images.githubusercontent.com/71296922/144913186-ace4eac6-1f84-41fd-9b39-96b3d9365b77.png)
Here we can see that small outlets are doing way better in selling seafood and starchy foods while high volume outlets are selling much less seafood, but doing much better in selling dairy and soft drinks. Medium outlets are pretty balanced, average sales numbers here are in the medium to high values.

In the next part of the project I am using different prediction models, such as Linear regression, Decision Tree model, Bagged Tree model and Random Forest model. After applying all four of them to this dataset, I am comparing the results:

1. Linear regression model:
 *Training performance: 0.5608195569734472
 *Testing performance: 0.5658893861862508
