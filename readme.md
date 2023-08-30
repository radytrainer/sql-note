## SQL Note
### #1 Basic query
```sql
CREATE TABLE table_name (col1 datatype, col2 datatype, col3 datatype, ...);
```
Example
```sql
CREATE TABLE users(
    user_id INTEGER PRIMARY KEY auto_increment,
    first_name varchar(255),
    last_name varchar(255),
    age int
);
```