# liquibase-springboot-h2-example
This is a sample project to demonstrate integration of Liquibase and H2 embedded database with Spring Boot application.

Liquibase is an open-source database schema change management solution which enables you to manage revisions of your database changes easily. Liquibase makes it easy for anyone involved in the application release process to:

- Eliminate errors and delays when releasing databases.
- Deploy and roll back changes for specific versions without needing to know what has already been deployed.
- Deploy database and application changes together so they always stay in sync.

For more details, please read the liquibase official documentation available at path: https://docs.liquibase.com/concepts/home.html

## Service Start Up Logs

![Service Logs](screenshots/1_service_logs.png?raw=true "Spring Boot & Liquibase Service Startup Logs")

## H2 Embedded Database Login Screen

![Service Logs](screenshots/2_h2_database_login.png?raw=true "H2 Embedded Database Login Screen")

## Employee Table created by Liquibase

![Service Logs](screenshots/3_employee_table.png?raw=true "Employee table created by Liquibase")

## Liquibase Tracking Table: DATABASECHANGELOG

![Service Logs](screenshots/4_databasechangelog_table.png?raw=true "DATABASECHANGELOG Liquibase Tracking Table")

## Liquibase Tracking Table: DATABASECHANGELOGLOCK

![Service Logs](screenshots/5_databasechangeloglock_table.png?raw=true "DATABASECHANGELOGLOCK Liquibase Tracking Table")
