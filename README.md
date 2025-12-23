# Nan-Stop Data Warehouse Design An End-to-End Data Engineering project focusing on Data Warehousing and ETL Pipeline automation.

## Project Overview
Goal: Consolidate disparate data sources (POS, Delivery) into a centralized Star Schema Data Warehouse.
Tech Stack: Apache NiFi, PostgreSQL, Docker.

## Key Features
Data Orchestration: Managed data flows using Apache NiFi for high-throughput ETL.
Infrastructure as Code: Fully containerized environment using Docker Compose for easy deployment.
History Tracking: Implemented SCD Type 2 to track historical changes in dimensions.

## How to Run
Run docker-compose up -d to start PostgreSQL and NiFi.
Access NiFi UI to view the NiFi_Flow.json.
