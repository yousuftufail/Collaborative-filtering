# Collaborative-filtering
This example is taken from DataCamp. In this exampe machine learning algorithm in spark is used to calculate the mean squared error between the original test data and predicted data. One variable "rating" is investigated and predicted.

# Important libraries

findspark
findspark.init("path_to_spark-3.1.2-bin-hadoop3.2")

pyspark.SparkConf
pyspark.context.SparkContext
sc = SparkContext.getOrCreate(SparkConf())
pyspark.sql.SparkSession
spark=SparkSession.builder.getOrCreate()
pyspark.mllib.recommendation.ALS & Rating

