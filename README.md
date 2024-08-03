# Customer-Recommendation-System

A simple hands-on exercise using TensorRec module in Python, a deep-learning ML algorithm that uses Tensorflow and Keras backend.

### Introduction:
Many recommendation algorithms exist, from a simple association rule to a slightly more complex K-Nearest Neighbor clustering, but to handle actual business case with millions of historical retail data, intertwined with hundreds of product category & customer hierarchy needs a robust & scalable solution. A prototype of collaborative filtering may work for a small grocery store, but to manage a chain of a few supermarket in a city, the amount of complexity can get multiplied enormously to millions of transactions. Hence, a better algorithm is needed to process the complexity yet produce meaningful and relevant results. Afer some research on various algorithms, a hybrid deep-learning algorithm is one of the best algorithms for complex and large datasets. Combining Pandas, Numpy, and SKLearn, together with TensorRec package module, we can harness the full potential of Python to produce a robust, solid, and relevant item recommendation.



### Types of Recommendation:
In retail, there are two kinds of recommendation commonly used, which are:

a. Content-based recommendation

This system uses item’s explicit features to represent interaction in between them. For example, if a user has purchased an item (e.g. a pair of socks), then the algorithm will recommend a similar or relevant item (e.g. shoes)

b. Collaborative Filtering

This system is based on the idea “User who likes X also likes Y”, where user’s historical transaction in between these two items is chained together in building relationships among other users. If user X had purchased milk, user Y, who is similar to user X but have not yet purchased this item, will receive a recommendation to buy it.

I will demonstrate a hybrid approach in this article, that processes both user similarity and item similarity.



### Retail Dataset:
This article will use an open dataset available on Kaggle. This dataset is a retail transaction, spanning from Jan 2011 to 2014, with full dataset and description available here - https://www.kaggle.com/darpan25bajaj/retail-case-study-data. The aim here is to understand how to apply recommendation system to retailers that contains many customers or to systems that consists of multiple users.


