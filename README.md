# Spotify-Python-AWS-Pproject

### Intruduction
In this projec, we will build as ETL (Extract, Transform,Load) pipeline using the Spotify API on AWS. The pipeline will retrieve data from the Spotify API, transform it in a desired format(json to csv, and load it into as AWS datastore

### Architecture
![Architecture Diagram](https://github.com/rajukalapala/spotify--python-aws-project/blob/main/Spotify_Data_Pipeline.jpg) 

###Services Used
1. **S3 (Simple Storage Servise):** Amazon S3 (Simple Storage Service) is a highly scalable object storage service that can store and retreive any amount of data from anywhere on the web.
2. **AWS Lamda:** AWS Lambda is a serverless compute service that lets you run your code without managing servers.
3. **Cloud Watch:** Amazon Cloud Watch is a monitoring service for AWS resources and the applications run on them. You can use Cloud Watch to track metrics, collect and moniter log files and set alarms.
4. **Glue Crawler:** AWS Glue Crawler is a fully managed service that automatically crawls your data sources, identifies data formates and schema to cerate as AWS Data Catalog
5. **Data Catalog:** AWS Glue Data Catalog is a fully managed metadata repository that makes it easy to discover and manage data
6. **Amazon Athena:** Amazon Athena is a interactive query service that makes it easy to analyse data in Amazon S3 using standard SQL.
