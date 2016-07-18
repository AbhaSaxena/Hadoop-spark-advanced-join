# Hadoop-spark-advanced-join
This is a hadoop project for joining 2 datasets using spark transformations with PySpark.

The 3 files genchanA.txt, genchanB.txt, genchanC.txt contain data in form of key-value pairs with showname(as key) and channel(as value). The other 3 files gennumA.txt, gennumB.txt and gennumC.txt contain key-value pairs with showname(as key) and no. of viewers(as value). Objective is to join the 2 datasets with channel name as key and total no. of viewers that channel has as value. 

The file spark_advanced_join_code contains the code to be written on PySpark terminal to join these datasets. 
Assumption, the 6 data files are in hdfs already. I have used cloudera hadoop platform for this project.
