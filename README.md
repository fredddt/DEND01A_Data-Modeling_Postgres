# 1. Data Modeling with PostgresSQL

#### #PostgresSQL, #Python, #Psycopg2
In this first project the following concepts and techniques are put into practice:

- Data modeling using PostgresSQL
- Definition of fact and dimension tables in a star schema
- Building of an ETL pipeline using Python.

## Motivation 
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.


Hence, the goal of this project is design a database in a star schema optimized for songplay analyis and to set up an ETL pipeline to process the seperate datasets.

## Database Schema