# Spotify End-to-End Data Engineering Project

## Introduction
This project builds ETL Pipeline using the Spotify API on AWS. This pipeline will retrieve data from the Spotify API, transform it to a desired format, and load it into an AWS data store.

### Architecture
![Architecture Diagram](https://github.com/muvva01/spotify-end-to-end-data-engineering-project/blob/main/spotify-end-to-end-data-pipeline-project_architecture.png)

### About Dataset/API
This API contains information about music artist, albums and songs

### Services Used
1. **S3 (Simple Storage Service)**
2. **AWS Lambda**
3. **Clous Watch**
4. **Glue Crawler**
5. **Data Catalog**
6. **Amazon Athena**

### Install Packages
...

pip install pandas                                                                                                                                                                                                   
pip install numpy                                                                                                                                                                                                    
pip install spotipy

...

### Project Execution Flow
Extract Data from API -> Lambda Trigger (every 1 hour) -> Run Extract Code -> Store Raw Data -> Trigger Transform function -> Transform Data and Load It -> Query Using Athena


