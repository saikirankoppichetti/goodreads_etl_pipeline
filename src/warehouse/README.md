# Data Warehouse Infrastructure

This repository contains the configuration and orchestration logic for managing data warehouse environments on AWS.

## warehouse_config.cfg file in warehouse folder contains  

```
[AWS]  
KEY=<AWS-KEY>
SECRET=<AWS-SECRET-KEY>
  
[CLUSTER]  
HOST='<Redshift Cluster Endpoint>'  
DB_NAME='<db-name>'  
DB_USER='<db-user-name>'  
DB_PASSWORD='<db-password>'  
DB_PORT=<db-port, default 5439>  
  
[IAM_ROLE]  
ARN=<Redshift ARN role>
  
  
[STAGING]  
SCHEMA=<Warehouse-staging-schema>  
  
[WAREHOUSE]  
SCHEMA=<Warehouse-schema>  
  
  
[BUCKET]  
LANDING_ZONE=<landing-zone-bucket>  
WORKING_ZONE=<working-zone-bucket>
PROCESSED_ZONE=<processed-zone-bucket>
```

## About the Developer

This project is maintained by Sai Kiran Koppichetti, an AI/ML Engineer with over 5 years of experience across machine learning, data science, and analytics. Sai Kiran specializes in building end-to-end RAG and agentic pipelines - including ingestion, chunking, embedding, and evaluation - alongside gradient-boosted risk models served on AWS. With a background in healthcare and financial services NLP, he focuses on developing robust data infrastructure to support clinical and analytical workflows.

### Contact Information

- GitHub: https://github.com/saikirankoppichetti
- LinkedIn: https://www.linkedin.com/in/saikirankoppichetti97/
- Email: koppichettisaikiran97@gmail.com