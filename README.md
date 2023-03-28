# E-commerce-shipping
Businees Case: Insights about the E-commerce website shipping products 
Practice Practice Practice, It is the ultimate advise for every starter in any field, The data is on the top of any field which needs everyday look.

That's why I would start with project follows project, I choose to do in parts method, to break into smaller parts is the second advise for all learners.

this is first part of many to work on the data set, to have a better view on what would you expect when you are working on data, how many days, how many parts data could be necessary for full analysis and prediction if needed.

Let's Dive and see.

Link for data set in Kaggle:

https://lnkd.in/dVyTm-sf

Attached Screens are from my trial, feel free asking for the code if you need it, or check others trials on Kaggle with the same link in data source
continue with the part one in analysis project to see what could case the shipment to be successfully shipped or not by have a better look on the relation between the different features and the class( shipped or not )
we will start now the Bivariate analysis.
we have some interesting results about the blocks that have most of shipment records, and also the way of shipment.
attached graphs to show sample of the results
Statistics, the expression is not commonly used when we talk about analysis, most of analysts are keen to perform the analysis using built-in functions in python or using visualization and put their insights depending on experience or recommendations, but what about giving some insights based on statistics.

In Part three we would like to perform some statistical analysis and see what will we have when putting some features together

After we consider the shipment mode and level of importance for products, we have reached to a conclusion that proportion of the success shipped rate is more related to how we treat them, and if the products have the same way of attention , the rate of success will be better no matter how we are shipping the product through flight, ship or road
for the last part, it comes always the prediction part, after we have cleaned, analyzed, and summarized the data, what will we do in the future, that is why we need to build a model to help us in predicting the result based on our data.

The suitable model algorithm technique to be used in this case is logistic regression, as we want to choose between two results, zero or one, so the perfect way to get the predictions.

First, we have to map all the categorical data and convert it to numerical data to be suitable for the regression model, In our model we have only 4 features that are needed to be mapped(warehouse_block,Gender, Product_importance, Ship_mode), we have converted them to numbers zeroes and ones, etc.

Second, we have to make scaling to avoid the outliers or fake errors in creating the model and make sure the normalization of features 

the features in our case need to be rescaled are ( weight , discount) as rest of the features we have the same range of data.

the model creation and training the model and have predictions, we have to evaluate the model itself to have a better look at the predictions of the model to be sure of the results and how far could we depend on the model in taking decisions.

The evaluation of the model gives us a look about the performance of the model, the results was good , if we have some edits on the model by dropping some features for example maybe we could get even much better results.

Now we can that we have done with this data set, you have the data analysis, statistics conclusions, and model prediction, may this helps in taking the decisions in such cases.
