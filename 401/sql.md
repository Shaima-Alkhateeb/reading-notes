# [Introduction to SQL](https://sqlbolt.com/lesson/end)

## What I learn from Introduction to SQL:



1. SELECT 

The SELECT statement is used to select data from a database.

```
SELECT DISTINCT column, AGG_FUNC(column_or_expression), …
FROM mytable
    JOIN another_table
      ON mytable.column = another_table.column
    WHERE constraint_expression
    GROUP BY column
    HAVING constraint_expression
    ORDER BY column ASC/DESC
    LIMIT count OFFSET COUNT;

```

2. INSERT 

The INSERT INTO statement is used to insert new records in a table.

```
INSERT INTO mytable
(column, another_column, …)
VALUES (value_or_expr, another_value_or_expr, …),
      (value_or_expr_2, another_value_or_expr_2, …),
      …;
```

3. UPDATE 

The UPDATE statement is used to modify the existing records in a table.

```
UPDATE mytable
SET column = value_or_expr, 
    other_column = another_value_or_expr, 
    …
WHERE condition;
```

4. DELETE 

The DELETE statement is used to delete existing records in a table.

```
DELETE FROM mytable
WHERE condition;
```

5. CREATE TABLE 

The CREATE TABLE statement is used to create a new table in a database.

```
CREATE TABLE IF NOT EXISTS mytable (
    column DataType TableConstraint DEFAULT default_value,
    another_column DataType TableConstraint DEFAULT default_value,
    …
);
```

6. ALTER TABL

The ALTER TABLE statement is used to add, delete, drop, or modify columns in an existing table .

Altering table to add new column(s)

```
ALTER TABLE mytable
ADD column DataType OptionalTableConstraint 
    DEFAULT default_value;
```


Altering table to remove column(s)
```
ALTER TABLE mytable
DROP column_to_be_deleted;
```

Altering table name
```
ALTER TABLE mytable
RENAME TO new_table_name;
```

7. DROP TABLE 

The DROP TABLE statement is used to drop an existing table in a database.

```
DROP TABLE IF EXISTS mytable;
```

![Introduction to SQL](https://user-images.githubusercontent.com/97349122/188694838-dd7c261c-4773-4023-aa0f-c21f8eddcadd.png)
