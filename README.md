# YouTube-Analytics-ETL
An end-to-end ETL data-pipeline on using AWS to perform analysis on structured and semi-structured data

# Goal
1. To perform data ingestion by building a mechanism to ingest data from different sources and developing a data-lake to store structured and semi-structured data
2. Build Analytics Reporting Dashboard 

# AWS Services:
AWS S3
AWS Glue
AWS IAM
AWS QuickSight 
AWS Lambda 
AWS Athena

Data Source:
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

# Architecture
![Data Architecture](https://user-images.githubusercontent.com/29363600/229392749-68c2aa1a-401f-4231-956b-4420a082d33f.jpeg)
