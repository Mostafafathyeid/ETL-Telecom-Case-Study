# ETL-Telecom-Case-Study-SSIS


The telecom company had specific requirements:

1-The pipeline ensures seamless handling of these files and moves them to the appropriate destination folder after processing.

2-Input Data Types and Columns: The company provided a table that outlines the required data types and columns for the input data. This information is crucial for accurately mapping and transforming the data during the ETL process. Additionally, another table specified the necessary transformation and data-cleaning steps for the desired output.

3-Rejected Records: To maintain data integrity, a dedicated table was created in the database to capture any rejected records during the data transformation phase. This allows for easy identification and resolution of data quality issues.

4-Auditing: An auditing table was implemented to track essential information, such as the number of records successfully transformed • Number of records rejected • Linking the file name with the corresponding auditing information
