# Big Data Processing Systems

This repository is about my adventure in learning and applying Big Data Processing Systems. I got my hands dirty with some of the coolest technologies out there like Hadoop, Apache Spark (PySpark, SQL, DataFrames), and Hive. Inside, you can find different scripts and code that explore how to process massive datasets, whether with distributed data processing, speeding things up with in-memory computing, or running SQL-like queries on structured and unstructured data. Spoiler: Spark’s in-memory processing is like adding rocket fuel compared to Hadoop’s more “slow and steady” approach.

The repo is divided into sections based on the tech I used. In the Hadoop folder, I wrestled with the classic MapReduce model (hence, more tutorial notebooks are also added below) for batch processing. In the PySpark section, I had way more fun with RDDs and their super-speedy in-memory parallel processing. Spark SQL was like putting on my SQL hat to query distributed data, and Spark DataFrames felt like I was working with the best-organized spreadsheet ever, but way more powerful. Finally, Hive showed me how to handle huge datasets with SQL on Hadoop—kind of like SQL’s older, wiser cousin:) Learning all this was great, and I loved comparing how these different frameworks handle the same problems in different ways.


# Hadoop map reduce and IP addresses 
Using the same docker image of  1, process the log of web entries using map-reduce to:
1. Count the number of unique IP addresses involved in the
attack.
2. For each interval of 10 seconds, provides the following
information: [number of request, average execution time,
maximum time, minimum time]
3. Create an inverted index that for each interval of 10 second,
has a list of (unique) IPs executing accesses.
