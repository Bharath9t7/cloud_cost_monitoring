# Cloud Cost Monitoring
This DBT project contains logic for converting raw cost data loaded from Azure, AWS, and GCP into consumable analytics tables.

Snowflake costs are also gathered from the `ACCOUNT_USAGE` tables.

## Snowflake setup
I used the [snowflake_init.sql](./snowflake_init.sql) file to create the top level databases, warehouse, and permissions that I use for deploying to Snowflake. This is pretty hashmap-specific, so feel free to use / modify / ignore this. 