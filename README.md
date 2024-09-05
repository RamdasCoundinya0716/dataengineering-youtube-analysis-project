# YouTube Data Analysis: A Data Engineering Project

## Overview

I created a comprehensive data engineering solution to handle, transform, and analyze structured and semi-structured YouTube video data. The focus was on extracting meaningful insights from metrics related to trending videos and categories across different regions. By leveraging AWS cloud services, I ensured the system was scalable and efficient, providing real-time analytics via an interactive dashboard.

## Problem Statement

YouTube generates an enormous amount of data every day, and traditional infrastructures struggle to process and analyze this effectively. The goal of this project was to build a scalable system that could ingest and manage vast datasets, process them efficiently, and deliver real-time insights into YouTube trends, all while ensuring security and availability.

## Solution

To address these challenges, I developed a scalable data pipeline using Amazon Web Services (AWS). I implemented an ETL system to ingest, transform, and store large volumes of YouTube data in a centralized data lake. Additionally, I created a real-time reporting dashboard with Amazon QuickSight, which visualized metrics such as video categories, views, and engagement, allowing for immediate access to actionable insights.

## Project Goals

1. **Data Ingestion** — I designed a system to ingest data from various sources into a centralized repository.
2. **ETL Pipeline** — I built an ETL pipeline to process raw data and convert it into structured formats for further analysis.
3. **Data Lake** — I centralized the storage of data in a scalable data lake to handle growing volumes of diverse data types.
4. **Scalability** — I ensured that the system could scale effortlessly as data size increased.
5. **Cloud Infrastructure** — I utilized AWS services to securely and efficiently manage large volumes of data.
6. **Reporting & Analytics** — I developed a real-time dashboard to offer insights into YouTube trends and performance metrics.

## AWS Services Used

1. **Amazon S3** — I used Amazon S3 to store and retrieve data securely, ensuring scalability and high performance.
2. **AWS IAM** — I managed access controls using AWS IAM to ensure secure, authorized use of resources.
3. **Amazon QuickSight** — I created an interactive dashboard with Amazon QuickSight to visualize real-time YouTube trends.
4. **AWS Glue** — I used AWS Glue to transform raw YouTube data into structured datasets for analysis.
5. **AWS Lambda** — I utilized AWS Lambda for automating the data pipeline, allowing seamless, serverless management.
6. **AWS Athena** — I employed AWS Athena to run interactive queries on data stored in S3, enabling in-place analysis without further transformations.

## Dataset

I worked with a dataset from [Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new) containing daily statistics on trending YouTube videos across different regions. The data includes video titles, channel names, publication times, tags, views, likes, dislikes, and comment counts. Each region has a separate data file, and the dataset also includes a category_id field that classifies videos by content type.
