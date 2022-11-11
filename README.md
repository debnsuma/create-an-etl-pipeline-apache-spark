# Creating an ETL Pipeline with Amazon EMR and Apache Spark (using PySpark)

In this tutorial, you learned about how you can build an ETL (Extract, Transform, and Load) pipeline for batch processing using Amazon EMR and Spark. During this process we will also learn about few of the use case of batch ETL process and how EMR can be leveraged to solve such problems. 

We are going to use [PySpark](https://spark.apache.org/docs/latest/api/python/) to intract with the Spark cluster. PySpark allows you to write Spark applications using Python APIs. 

## Requirements 

We assume that you have the following:

- An AWS account 
- An IAM user that has the access to create IAM role, which will be used to trigger or execute the Spark job 
- Basic understanding of Python


## Use case and problem statement

For this use case, we will take [YouTube Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new) dataset and shall clean, analyse and process that data to get some insights about different videos we have in that data set. We should be able to query:

1. Which catagoty of the videos are most popular (may be videos with max. no. of `likes`)
1. Which catagoty of the videos are not all that popular (may be videos with max. no. of `dislikes`)





And we will do that by analysing YouTube video statistics data by cleaning, processing and finally analuzing the data in an automated and optimized way.


