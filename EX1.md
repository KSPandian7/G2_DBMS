# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```sql
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```

### OUTPUT:
![Alt text](270861020-d4078461-29d3-4714-aa2b-d859b4552fa6.png)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table student add department char(30);
```

### OUTPUT:
![Alt text](270861141-2c22e52a-f697-4647-8c27-19b5dbb87d15.png)

### 3) Drop the student table
 
### SQL QUERY: 
```sql
drop table student;
```

### OUTPUT:
![Alt text](270861215-d0c90400-b82a-4d48-898f-1d18b60f2f8a.png)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
truncate table student;
```

### OUTPUT:
![Alt text](270861260-a7cf6059-f7e7-4b7f-9db9-8e45b0246324.png)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table student rename to mystudent;
```

### OUTPUT:
![Alt text](270861345-9d838847-3a92-4ec4-a2e6-a98d06085ad0.png)



### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.