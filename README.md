# Airflow-Data-Pipeline-of-Online-Retail-Transactional-Dataset
Airflow-driven data pipeline for UK-based online retail analytics. Leverage Google BigQuery, dbt for transformation, Soda for data testing, and visualize insights with Metabase. Explore transnational data from 01/12/2010 to 09/12/2011.


# Airflow Data Pipeline for UK Online Retail Analytics

## Overview

This project implements an end-to-end data pipeline for analyzing transactions from a UK-based online retail company. The dataset covers the period from 01/12/2010 to 09/12/2011 and includes transactions for a variety of unique all-occasion gifts.

## Tech Stack

- **Apache Airflow:** Orchestrates the data pipeline and workflow.
- **Google BigQuery:** Stores and manages large-scale analytics data.
- **dbt (data build tool):** Handles data transformations and modeling.
- **Soda:** Ensures data quality through automated testing.
- **Metabase:** Provides visualization and exploration of analytics insights.

## Project Structure

- **dags/:** Contains Airflow DAGs (Directed Acyclic Graphs) for the pipeline.
- **sql/:** SQL queries for transformations and dbt models.
- **tests/:** Quality tests using Soda for data validation.
- **visualizations/:** Dashboard visualizations in Metabase.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/HemantDeshmukh026/Airflow-Data-Pipeline-of-Online-Retail-Transactional-Dataset.git

2. Set up your Airflow environment and dependencies.

3. Configure the necessary credentials for BigQuery an other services.

4. Run the Airflow DAG to initiate the data pipeline:
