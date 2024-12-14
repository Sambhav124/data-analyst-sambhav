# Projects
## Project 1: AWS Data Analytic Platform - Phase 1
This project focuses on creating a scalable and secure data analytics platform to process and analyze urban challenges in the City of Vancouver using AWS. Phase 1 centers on Illegal Dumping Cases and addresses issues such as:

**Pipeline 1:** Data ingestion and profiling from multiple sources like web and mobile.

**Pipeline 2:** Data cleaning and schema validation using AWS Glue DataBrew.

**Pipeline 3:** SQL-based exploratory analysis through Amazon Athena.

**Pipeline 4:** Secure data storage using S3 buckets with KMS encryption and versioning.

**Pipeline 5:** Visualizing processed data using CloudWatch dashboards.

**Architecture Overview:**

Amazon S3 for raw and processed data storage.
AWS Glue for ETL processing and data cataloging.
Amazon Athena for querying and analysis.
CloudWatch for real-time monitoring and insights.

<img width="526" alt="image" src="https://github.com/user-attachments/assets/66dbf4ea-e822-4166-8d7f-58ac51ebfb44" />

# Project 2: AWS Data Analytic Platform - Phase 2
## Phase 2 expands the platform's functionality to include additional datasets and analyses for High Water Consumption and Graffiti Cases. This phase emphasizes enhancing data security and observability.

**Pipeline 1:** Enrichment of datasets using AWS Glue DataBrew.

**Pipeline 2:** Advanced SQL queries for spatial and temporal analysis via Athena.

**Pipeline 3:** Data governance using Glue for sensitive data detection and quality checks.

**Pipeline 4:** Observability features using CloudWatch for real-time cost monitoring and performance insights.

**Pipeline 5:** Secure replication using cross-bucket rules with KMS.
<img width="526" alt="image" src="https://github.com/Sambhav124/data-analyst-sambhav/blob/a92c85df3f23154e979557f60ee4854ce190eb3e/Screenshot%202024-12-10%20163558.png" />


**Architecture Enhancements:**

Inclusion of conditional routing for data based on quality checks.
Additional widgets in CloudWatch for cost, resource usage, and data growth.

## Implementation Steps (Summary for both Phases):

Data Ingestion: Uploaded datasets into Amazon S3, organized by processing stages (raw, cleaned, processed).
Data Profiling and Cleaning: Used AWS Glue DataBrew for profiling and handling missing values, schema mismatches, and transformations.
Analysis and Insights: Queried datasets in Athena to derive insights and trends.
Visualization: Configured CloudWatch dashboards for stakeholder-friendly insights.
