## SQL Note
### #1 Basic query
1 - CREATE TABLE
```sql
CREATE TABLE table_name (col1 datatype, col2 datatype, col3 datatype, ...);
```
Example
```sql
CREATE TABLE users(
    user_id INT PRIMARY KEY AUTO_INCREMENT,
    first_name  VARCHAR(25),
    last_name VARCHAR(25),
    age INT
);
```
2 - GET DATA FROM TABLE
```sql
SELECT * FROM table_name;
```
Example
```sql
SELECT * FROM users;
```
3 - INSERT DATA INTO  TABLE
```sql
INSERT INTO table_name (col1, col2, col3,...) VALUES(value1, value2, value3, ..);
```
Example
```sql
INSERT INTO users(first_name, last_name, age) VALUES('rady', 'y', 29);
```
4 - DELETE ONE DATA FROM TABLE
```sql
DELETE FROM table_name WHERE id = value;
```
Example
```sql
DELETE FROM users WHERE user_id = 1;
```