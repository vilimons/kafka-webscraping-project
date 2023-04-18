# Kafka Webscraping Project

## Introduction
In this project, a dataframe was created from webscraping. After cleaning the data, the dataframe was saved as CSV format. Then Kafka was used to produce and consume this data and send to AWS s3 bucket. After this process, the data is extracted and collected to AWS Glue Data Catalog by a Crawler and finally sent to AWS Athena, so the final consumer can query and analyze it.

## Architecture ![kafka-project-workflow](https://user-images.githubusercontent.com/48607584/232667925-09fd03e0-edad-42a6-9f62-2f48e5132558.png)

## Technology used

- Programming Language: Python
- Cloud Service: AWS
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka
