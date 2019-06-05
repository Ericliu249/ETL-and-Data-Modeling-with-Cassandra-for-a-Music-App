# ETL and Data Modeling with Cassandra for a Music App
- Author: Yang Liu
- Contact: eric.liu.249@gmail.com

## Backgroud

A startup called Sparkify wanted to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team was particularly interested in understanding what songs users are listening to. However, there was no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

In this case, as a Data Engineer, I created an Apache Cassandra database which can create queries on song play data to answer the questions. I performed data modeling with Apache Cassandra and completed an ETL pipeline using Python. The ETL pipeline  transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables. Additionally, I tested the database by running queries given to you by the analytics team from Sparkify to create the expected results.

## Tools

- Apache Cassandra
- Python 3.5+
- os
- re
- glob
- pandas
