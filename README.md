# ETL-Telecom-Case-Study-SSIS

Description:
files contain the main transaction processes that the customers have completed

Objectives:

1-Pipeline: The SSIS package designed here manages the ingestion, processing, and transfer of transaction files to designated destination folders after the completion of processing.

2-Input Data Schema and Columns: The company's provided schema details the requisite data types and column structure for incoming data. This schema is pivotal in accurately mapping and transforming data during the ETL (Extract, Transform, Load) process. Additionally, a transformation guide outlines the necessary steps for achieving the desired output.

3-Rejected Records Handling: Upholding data integrity, a dedicated database table captures rejected records encountered during the data transformation phase. This facilitates easy identification and resolution of data quality issues.

4-Auditing Mechanism: An auditing table has been incorporated to track vital information, including:
  Successfully transformed records
  Rejected record count
  Association between file names and relevant auditing information for traceability and analysis.
