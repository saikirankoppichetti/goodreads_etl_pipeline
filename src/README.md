# AWS Data Ingestion and Processing Pipeline

This repository contains the source code and configuration required to manage data workflows on AWS. The system facilitates the movement of datasets through various processing stages, ensuring data integrity and accessibility across cloud environments.

## Configuration

The config.cfg file in the src folder contains the necessary AWS credentials and bucket definitions:

```
[AWS]  
KEY=<AWS-KEY>
SECRET=<AWS-SECRET-KEY>
  
[BUCKET]  
LANDING_ZONE=<Landing zone bucket name>
WORKING_ZONE=<working zone bucket name>  
PROCESSED_ZONE=<processed zone bucket name>  
  
[FILES]  
NAME=author.csv,book.csv,reviews.csv,user.csv
```

## Technical Overview

The pipeline is designed to automate the lifecycle of data within an AWS ecosystem. It manages the transition of files between three primary zones:

- Landing Zone: The entry point for raw data ingestion.
- Working Zone: The staging area for data transformation and cleaning.
- Processed Zone: The final repository for validated, analysis-ready data.

The current configuration is optimized for processing author, book, reviews, and user datasets, utilizing Python and AWS SDKs to ensure reliable data movement.

## Maintainer

Sai Kiran Koppichetti
AI/ML Engineer
Email: koppichettisaikiran97@gmail.com
GitHub: https://github.com/saikirankoppichetti
LinkedIn: https://www.linkedin.com/in/saikirankoppichetti97/

About the Developer:
Sai Kiran is an AI/ML Engineer with over 5 years of experience across machine learning, data science, and analytics. He specializes in building end-to-end RAG and agentic pipelines, focusing on ingestion, chunking, embedding, and evaluation. With a background in healthcare and financial services NLP, he focuses on developing trusted systems and gradient-boosted risk models served on AWS infrastructure.