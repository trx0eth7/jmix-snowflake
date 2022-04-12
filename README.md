### JMix + snowflake datastore example

Issues:
 * Unsupported datatype, see https://docs.snowflake.com/en/sql-reference/data-types-unsupported.html
   it requires custom datatype converter (example: CLOB -> VARCHAR)
 * Jmix plugin doesn't support snowflake database type (Data Stores)
   it requires defining own gradle's tasks to generate ddl liquibase changelog xml files