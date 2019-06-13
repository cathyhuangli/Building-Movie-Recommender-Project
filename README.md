# Movie Recommender-System Project

## Goal
Build Movie-Recommender-System that can answer questions from different angles and compare the performance of different models.

## Data description
source: https://grouplens.org/datasets/movielens/
with the dataset with size 100k. I am using this dataset as it is very detailed both in user and item info for analysis. There are three main dataset that are used in this project from this movie lens data collection, ‘u.data’,’u.item’,’u.user’,’ua.test’. The size (rows, cols) of u.data, u.item and u.user datasets are (100000, 4), (1682, 24), (943, 5) respectively. The ua.test is the test dataset that set side for accuracy calculating in Part3.

## Methodology and Implementation Process Exploration
In this project, I have processed the dataset with analysis and visualization tools from python library numpy, panda, matplotlib, scikit learn; performed classification, to be specific, K nearest neighbor classification; implemented user-based collaborative filtering recommender, item-based collaborative filtering recommender and matrix factorization; and evaluation the results.

Following is the flow chart of methodology and structure of this project:
![Methodology](https://github.com/cathyhuangli/Recommender-System/blob/master/Methodology.png)

## Result: 
From the comparison of the result, we can see the Matrix_factorization based recommender is more accurate than the other two recommenders, but it also takes a much longer time to generate the prediction result. User_based recommender takes a little bit longer than the item_based recommender, and the Mean absolute error is also a little higher than item_based recommender. 
![Result Comparision](https://github.com/cathyhuangli/Recommender-System/blob/master/Result%20Comparison.png)
