I completed a project using **Informatica IICS** and **Snowflake** database to establish an end-to-end ETL pipeline. DataSet: 2019 Salesv1.csv
The project involved processing data stored in flat files through the following steps:

1. Data Backup in Data Warehouse (Snowflake):
   Initially, sales data from flat files was loaded into Snowflake as a backup in the data warehouse.

2. Data Quality and Profiling:
  Before proceeding to the staging area, thorough data profiling and quality checks were performed to ensure ETL process integrity.
  Detailed profiling results are documented in a report (Profiling_2019SalesData_Run1.xlsx)

3. Data Staging Area (Snowflake):
  The sales data was then loaded into Snowflake's staging area to prepare for transformations based on project requirements.

4. Transformations Based on Business Requirements:
  Comprehensive transformations were applied to the staged data to align with specific business rules and needs.

5. Golden Layer (BI/Production Layer) for Analytics:
  The transformed data was loaded into the Golden Layer (also known as the BI or Production layer), optimized for advanced analytics and reporting purposes.

Each step of the ETL pipeline was automated using mapping tasks and scheduled for execution at predefined intervals. This automated task flow ensured that data tasks were executed sequentially.
![TaskFlow_ETL_pipeline_Project](https://github.com/MeenakshiDevara/End-to-End-ETL-Pipeline-for-Sales-Data/assets/70430811/d52538c6-c948-46ed-87c6-b2a066b1bc3b)
