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

### Step 1: Clone the Repository
Begin by cloning the repository to your local machine using the following command:

```bash
git clone https://github.com/HemantDeshmukh026/Airflow-Data-Pipeline-of-Online-Retail-Transactional-Dataset.git
```

### Step 2: Set Up Your Airflow Environment
Configure your Airflow environment and ensure that all dependencies are set up appropriately. This step is crucial for the smooth execution of the data pipeline.

### Step 3: Configure Necessary Credentials
To guarantee seamless functionality, it is essential to configure the required credentials for Google BigQuery and any other services involved in the project.

### Step 4: Run the Airflow DAG
Initiate the data pipeline by running the Airflow Directed Acyclic Graph (DAG). This action kickstarts the process, allowing you to explore and analyze the extensive dataset effectively.

Congratulations! You are now ready to embark on your journey with the Airflow Data Pipeline for UK Online Retail Analytics. Explore the vast realm of transactional data and uncover valuable insights from 01/12/2010 to 09/12/2011.
