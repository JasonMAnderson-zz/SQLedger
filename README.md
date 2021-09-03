
# Azure SQL Database Ledger

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FJasonMAnderson%2FSQLedger%2Fmain%2Fazuredeploy.json)


This template allows you to create an [Azure SQL Database](https://docs.microsoft.com/azure/azure-sql/database/sql-database-paas-overview) with ledger database enabled, ensuring that all tables created in the database are updatable ledger tables.  Creation of append-only ledger tables is supported on a ledger database by specifying the APPEND_ONLY = ON argument in your CREATE TABLE T-SQL statement.
`Tags: Azure, SQL database`
