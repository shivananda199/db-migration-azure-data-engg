# db-migration-azure-data-engg

An end-to-end data engineering project involving:
- Migration of on-premises SQL Server database to Azure Cloud
- Data Pipeline creation using Azure Data Factory to automate data transfer from SQL Server to Azure Data Lake
- Usage of Azure Databricks to transform raw data into analytical dataset
- Creation of Azure Synapse Analytics SQL Database to query data in data lake for reporting needs
- Creation of Power BI dashboards to visualize key metrics and display insights

Prerequisites:
- Knowledge of SQL and Python
- Fundamentals of Azure Cloud services (Data Factory, Data Lake, Azure Databricks, Synapse Analytics, Key Vault) and Power BI

## Architecture Diagram

![architecture-diagram](azure-architecture-diagram.png?raw=true)


## Project Steps
- [0_project_setup](./0_project_setup/README.md)
- [1_data_ingestion](./1_data_ingestion/README.md)
- [2_data_transformation](./2_data_transformation/README.md)
- [3_data_loading](./3_data_loading/README.md)
- [4_data_reporting](./4_data_reporting/README.md)