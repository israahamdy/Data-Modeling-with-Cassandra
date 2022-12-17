# Data-Modeling-with-Cassandra

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app.
The analysis team is particularly interested in understanding what songs users are listening to.
Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions.
My role is to create a database for this analysis, test the database by running given queries by the analytics team from Sparkify to create the results.


In this project, I'll apply what I've learned on data modeling with Apache Cassandra and complete an ETL pipeline using Python. 
Model data by creating tables in Apache Cassandra to run queries.
The ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

### Datasets
For this project, I'll be working with one dataset: event_data. 
The directory of CSV files partitioned by date. 

### Project file

The project includes one Jupyter Notebook file, in which:

 - process the event_datafile_new.csv dataset to create a denormalized dataset
 - model the data tables keeping in mind the queries need to run
 - queries that need to model data tables for
 - load the data into created tables in Apache Cassandra and run queries
 
### Project Steps

- Modeling NoSQL database or Apache Cassandra database
- Design tables to answer the queries
- Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
- Develop CREATE statement for each of the tables to address each question
- Load the data with INSERT statement for each of the tables


- Include IF NOT EXISTS clauses in CREATE statements to create tables only if the tables do not already exist. 
  also include DROP TABLE statement for each table, this way can run drop and create tables whenever want to reset database and test ETL pipeline
- Test by running the proper select statements with the correct WHERE clause
