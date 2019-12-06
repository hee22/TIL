# Mysql - Basic syntax

## 1. `Create`

1. `CREATE DATABASE <database_name>;` : create db
2. `USE <database_name>'` : choice db
3. `SELECT DATABASE()` : check db
4. `CREATE TABLE <table_name>(column_name_1 col1_dtype, column_name_2 col2_dtype);` : create table


## 2. `Alter`

1. `ALTER DATABASE test CHARACTER SET = utf8;` : encoding
2. `ALTER TABLE table_name ADD col_name TEXT;` : add column
3. `ALTER TABLE table_name DROP col_name;` : delete column

## 3. `Delete`

1. `DROP DATABASE db_name;` : delete db
2. `DROP TAbLE table_name;` : delete table

## 4. `Insert`

1. `INSERT INTO <table_name>(<column_name_1>, <column_name_2>, ...) VALUES(<value_1>, <value_2>, ...)`;

## 5. `Select`

1. `SELECT col_name FROM table_name;`; basic
2. `SELECT col_name as C FROM table_name;` : alias
3. `SELECT DISTINCT(col_name) FROM table_name;` : deduplication
4. `SELECT col_name FROM table_name WHERE <condition>;` : condition
5. `SELECT col_name FROM table_name ORDER BY col_name asc|desc;` : sort
6. etc(CONCAT, LIKE, IN, LIMIT, ...)

## 6. `Groupby`

1. `SELECT col_name FROM table_name GROUP BY col_name` : basic
2. methods : COUNT, MAX, MIN, SUM, AVG, ...

## 7. `Having`
1. `SELECT col_name FROM table_name GROUP BY col_name HAVING <condition>;` : condition in groupby

## 8. `Etc`
1. `UPDATE table_name SET col1_name = value1, col2_name=value2 WHERE <condition>;` : update
2. `DELETE FROM table_name WHERE <condition>;` : delete


## TODO
sub query
