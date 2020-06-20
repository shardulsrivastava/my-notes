# Spark Notes


## Spark Streaming vs Spark Structured Streaming

Well, there is always confusion as to which one to use, here is an article summairizing it nicely.

https://dzone.com/articles/spark-streaming-vs-structured-streaming

## Language Support for Spark and Python
Spark streaming kafka integration doesn't support Python for kafka version higher than 0.10, it only support Scala and Java, details cane be found here :
https://spark.apache.org/docs/latest/streaming-kafka-0-10-integration.html

however Spark streaming is old and isn't actually stream processing as it divides the data into micro batches to prcess, so its best to use Spark structured streaming which support all three languages Scala,Java,Python.
https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html

Spark structured straming kafka integration guide:
https://spark.apache.org/docs/latest/structured-streaming-kafka-integration.html


## Spark Scala




## PySpark





