# Analyzing 10Gb of Yelp Reviews Data

In this project, we are going to provision a Spark cluster on AWS EMR, connect it to a Jupyter Notebook and then run a series of queries using Pyspark based on Yelp's business, reviews and user data. This dataset uses AWS s3 bucket to load the data. The json format data is from [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset). The following are the steps to conduct the analysis.

## Steps

Part I: Installation and Initial Setup

Part II: Analyzing Categories (Business dataset)


How many unique categories are represented in this dataset?
What are the top 20 most popular business categories?(Horizontal Bar Chart)


Part III: Do Yelp Reviews biased from the average rating? (Review dataset)

Do Yelp Reviews Skew Negative? Is it true that people who write a review are those who are more dissatisfied or more satisfied with the service received？

Part IV: Analzing Users (User dataset join Business and Review Dataset)

Should Elite users be trusted?


## Cluster and Notebook Configs
![cluster](https://github.com/KY0409/Project2/blob/main/cluster_configuration.png)
![notebook](https://github.com/KY0409/Project2/blob/main/notebook_configuration.png)

