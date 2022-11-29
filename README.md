# big-data-challenge
This project explores using pyspark to perform ETL on a dataset. The data used is [Amazon customer reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) data. An AWS-RDS is created and used to store the transformed data. 
# Contents
- level-1:
    - reviews_1.ipynb: extracts data from amazons reviews api, transforms it to fit database schema and loads it into AWS-RDS database
    - vine_schemas.sql: used to create database schema