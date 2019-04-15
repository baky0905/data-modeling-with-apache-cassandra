# Project: Data Modeling with Apache Cassandra

## Overview

In this project, I applied what I have learned on data modeling with Apache Cassandra and completed an ETL pipeline using Python. I modelled the data by creating tables in Apache Cassandra to run queries. There is an ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

## Dataset

For this project, there is only one dataset: `event_data`. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:

```txt
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```

![](https://raw.githubusercontent.com/baky0905/data-modeling-with-apache-cassandra/master/images/image_event_datafile_new.jpg)

## Explanation of the files in the repository

In addition to the **dataset from the event_data folder**, the project workspace includes **two more files**:

1.  [`Project_1B_ AppacheCassandra.ipynb`](https://github.com/baky0905/data-modeling-with-apache-cassandra/blob/master/Project_1B_%20AppacheCassandra.ipynb) contains two parts 

   a) Part I. ETL Pipeline for Pre-Processing the csv files from the event_data folder-

   b) Part II. Apache Cassandra coding portion of the project

2. `event_datafile_new.csv`contains preprocessed individual csv files in a form of one denormalized and merged csv.

   

