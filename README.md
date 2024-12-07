# Final Project: Pipeline with Airflow, dbt, and Snowflake

##     ---Students---
# Ismanol Ramírez 2020-0098
# Ricky De La Cruz 2018-1405
# Jhonatan Hernandez 2022-0023

## Link del video explicando:
https://drive.google.com/file/d/1QjykweCzlHyBW3N5vvC_0eJ6WGWgWSD9/view?usp=drive_link

## Project Description
This project involves building a data pipeline using *Apache Airflow, **dbt, and **Snowflake*, based on the Quick Lab provided by Snowflake. The pipeline will extract, transform, and load (ETL) data into a cloud-based data warehouse while following collaboration best practices using GitHub.

## Objectives
- Automate data workflows using *Apache Airflow*.
- Transform raw data into meaningful insights with *dbt*.
- Store and manage data efficiently in *Snowflake*.
- Demonstrate teamwork through *GitHub commits* and *Pull Requests*.

---

## Requirements
To complete this project, you will need:
- *Docker*: To set up the environment and run containers.
- *Apache Airflow*: To orchestrate the workflow.
- *dbt (Data Build Tool)*: To perform transformations.
- *Snowflake*: As the data warehouse.
- *Python* and *SQL*: For scripting and queries.
- A *GitHub account*: For project collaboration and code management.

---

## Pipeline Overview
This project follows the ELT (Extract, Load, Transform) approach:
1. *Extract*: Simulate or use real data sources to extract raw data.
2. *Load*: Import the extracted data into Snowflake.
3. *Transform*: Process and organize the data using dbt.
4. *Orchestrate*: Use Airflow to automate and manage the workflow.
5. *Validate*: Test the pipeline's functionality and ensure data quality.

---


### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
