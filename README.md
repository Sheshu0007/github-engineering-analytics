# GitHub Engineering Analytics Data Pipeline

## Project Overview

An end-to-end Data Engineering project that collects engineering activity data from the GitHub REST API, processes it, stores it, and generates analytics.

## Business Objectives

- Analyze repository activity and developer contributions.
- Track pull request completion time.
- Monitor issue creation and resolution.
- Analyze GitHub Actions workflow performance.

## Technology Stack

- Python – API ingestion and data processing
- GitHub REST API – Data source
- PostgreSQL – Relational database
- Apache Airflow – Workflow orchestration
- AWS S3 – Data lake storage
- Parquet – Analytical file format
- Amazon Athena – SQL analytics
- Power BI – Dashboard development
- Docker – Local development environment

## Pipeline Architecture

GitHub REST API → Python Ingestion → Bronze → Transformation → Silver → Gold → Analytics → Power BI

## Project Status

Phase 1 – Project setup and environment preparation.

## Data Security

API credentials and secrets must be stored securely in environment variables and must never be committed to Git."# github-engineering-analytics" 
