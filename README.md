BIRD – Data Migration POC

Day 1: Assessment and Pre-Planning

•	Review the current on-premise SQL Server database schema, tables, and stored procedures.
•	Identify dependencies and relationships between database objects.
•	Assess any custom scripts or jobs that might need modification for Azure compatibility.
•	Install and configure Azure Data Factory (ADF) on the destination Azure SQL server.
•	Set up a test environment on Azure to simulate the migration.

Day 2: Data Migration Setup
•	Identify and prioritize tables for migration based on dependencies.
•	Set up Azure SQL Database with required configurations (e.g., collation, compatibility level).
•	Develop and test Azure Data Factory pipelines for initial data extraction from the on-premise database to Azure SQL Database.

Day 3: Schema and Object Migration
•	Script out the database schema and objects from the on-premise SQL Server.
•	Modify scripts to address any Azure SQL compatibility issues.
•	Execute schema migration scripts on the Azure SQL Database.
•	Validate that all tables, views, and stored procedures have been created successfully.

Day 4: Data Transformation Development
•	Identify and plan data transformations needed during migration.
•	Develop and test transformation logic using Azure Data Factory.
•	Implement and test additional data cleansing and transformation logic.

Day 5: Incremental/Transactional Data Migration
•	Configure Azure Data Factory pipelines for incremental data extraction.
•	Creation of break points and logs to be captured.

Day 6: Error Handling setup
•	Designing of failure and error handling during migration or transformation.
•	Testing of error handling and configuring the monitoring process.

Day 8: Validation and Testing
•	Conduct comprehensive data validation checks to ensure data integrity.
•	Validate that all transformations are applied correctly.
•	Perform performance testing and optimization.
•	Identify and address any issues or performance bottlenecks.

Day 9-10: Finalization and Deployment
•	Document the migration process and any troubleshooting steps.
•	Obtain final approval and sign-off.
•	Execute the final migration.
•	Monitor for any issues during and after the migration.
Day 11: Post-Migration
•	Conduct post-migration testing and validation.
•	Update connection strings and configurations in applications pointing to the new Azure SQL Database.
•	Monitor the Azure SQL Database for performance and optimization opportunities.
