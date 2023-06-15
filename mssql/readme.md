## 1. Create Database

```sql
CREATE DATABASE database_name;
```

## 2. Create Table

```sql
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
   ....
);
```

## 3. Insert Data

```sql
INSERT INTO table_name (column1, column2, column3,...)
VALUES (value1, value2, value3,...);
```

## 4. Select Data

```sql
SELECT column1, column2, ...
FROM table_name;
```

## 5. Where Clause

```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition;
```

## 6. Update Data

```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
```

## 7. Delete Data

```sql
DELETE FROM table_name WHERE condition;
```

## 8. Order By

```sql
SELECT column1, column2, ...
FROM table_name
ORDER BY column1, column2, ... ASC|DESC;
```

## 9. Group By

```sql
SELECT column_name(s)
FROM table_name
WHERE condition
GROUP BY column_name(s)
ORDER BY column_name(s);
```

## 10. Having Clause

```sql
SELECT column_name(s)
FROM table_name
WHERE condition
GROUP BY column_name(s)
HAVING condition
ORDER BY column_name(s);
```

## 11. Joins

### Inner Join

```sql
SELECT column_name(s)
FROM table1
INNER JOIN table2
ON table1.column_name = table2.column_name;
```

### Left (Outer) Join

```sql
SELECT column_name(s)
FROM table1
LEFT JOIN table2
ON table1.column_name = table2.column_name;
```

### Right (Outer) Join

```sql
SELECT column_name(s)
FROM table1
RIGHT JOIN table2
ON table1.column_name = table2.column_name;
```

### Full (Outer) Join

```sql
SELECT column_name(s)
FROM table1
FULL JOIN table2
ON table1.column_name = table2.column_name;
```

## 12. Create View

```sql
CREATE VIEW view_name AS
SELECT column_name(s)
FROM table_name
WHERE condition;
```

## 13. Create Stored Procedure

```sql
CREATE PROCEDURE procedure_name
AS
sql_statement
GO;
```

## 14. Drop/Delete

```sql
DROP DATABASE database_name;
DROP TABLE table_name;
DROP INDEX index_name ON table_name;
DROP VIEW view_name;
DROP PROCEDURE procedure_name;
```

## 15. Alter

```sql
ALTER DATABASE database_name MODIFY NAME = new_database_name;
ALTER TABLE table_name ADD column_name datatype;
ALTER TABLE table_name DROP COLUMN column_name;
ALTER TABLE table_name ALTER COLUMN column_name datatype;
```
