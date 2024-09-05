YouTube Data Analysis: A Data Engineering Project
Overview
This project focuses on managing, transforming, and analyzing both structured and semi-structured YouTube video data to gain insights into video categories and trending metrics across various regions. By leveraging a cloud-based architecture, the project ensures scalability and efficient data processing, while providing real-time analytics through a user-friendly dashboard.

Problem Statement
YouTube generates an enormous amount of data every day, and it is difficult to manage and analyze this data efficiently using traditional, on-premise infrastructure. The challenge was to design a system that could handle diverse datasets, scale with increasing data volumes, and provide real-time insights into trending videos. We also needed to ensure secure data storage and easy access to these insights.

Solution
To address these challenges, we developed a scalable data pipeline using Amazon Web Services (AWS). By building an ETL (Extract, Transform, Load) system and leveraging various AWS services, we were able to ingest, transform, and store large volumes of data in a centralized data lake. A real-time reporting dashboard was built using Amazon QuickSight to provide immediate insights into key metrics such as video trends, categories, views, and user engagement.

Project Goals
Data Ingestion — Implement a robust mechanism to ingest structured and semi-structured data from multiple sources into a centralized repository.
ETL System — Develop an ETL pipeline to process raw data, transforming it into a structured format for analysis.
Data Lake — Store large volumes of diverse data in a centralized data lake, ensuring easy access and management.
Scalability — Design the system to scale seamlessly as the volume of data increases.
Cloud Infrastructure — Utilize AWS cloud services to manage and process vast amounts of data efficiently and cost-effectively.
Reporting & Analytics — Build a real-time dashboard to provide insights on trending videos and their performance across different categories.
AWS Services Used
Amazon S3 — An object storage service to securely store and retrieve YouTube data, ensuring high scalability and performance.
AWS IAM — Used to securely manage access to AWS services, ensuring data security and compliance.
Amazon QuickSight — A serverless business intelligence (BI) tool to create real-time dashboards and visualizations for analyzing YouTube metrics.
AWS Glue — A serverless ETL service for transforming raw YouTube data into structured datasets for analysis.
AWS Lambda — A serverless compute service to automate and manage the data pipeline without the need for managing servers.
AWS Athena — An interactive query service allowing us to analyze data directly in S3 without the need to move or transform it further.
Dataset
We used a publicly available dataset from Kaggle that contains daily statistics on popular YouTube videos across various regions. The dataset includes information such as video titles, channel names, publication times, tags, views, likes, dislikes, and comment counts. Each region has its own set of data files, and JSON files include a category_id field that categorizes the videos by content type.
