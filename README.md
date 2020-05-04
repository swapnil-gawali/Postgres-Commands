# Postgres-Commands

### Select

<br />

* Select all fields from table
```sql
SELECT * FROM <table_name>
```

* Select specific columns from table
```sql
SELECT <column_name1>, <column_name2> FROM <table_name>
```

* Select unique (non-duplicates) values from table
```sql
SELECT DISTINCT FROM <table_name>
```

* Get count
```sql
SELECT COUNT(<column_name> || *) FROM <table_name>
```
> Example
```sql
SELECT COUNT(*) FROM t_users

SELECT COUNT(city) FROM t_users
```