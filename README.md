# G2_DBMS
## Date: 4/8/23 
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
```
 create table student(
  rollno char(5),
  name varchar(20),
  age char(5),
  address varchar(100),
  phoneno char(15));
```

### OUTPUT:
![image](https://github.com/BharathCSEIOT/F2_DBMS/assets/122793480/81bda2c1-e02e-45f4-b50d-a6439efeea07)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
ALTER TABLE student
ADD department varchar(30);
```
### OUTPUT:
![image](https://github.com/BharathCSEIOT/F2_DBMS/assets/122793480/18d4f8f3-4829-4960-8ed5-998b9f4d7a72)


### 3) Drop the student table
 
### SQL QUERY: 
```
 drop table student;
```
### OUTPUT:
![image](https://github.com/BharathCSEIOT/F2_DBMS/assets/122793480/169fbbf9-4c52-40d1-95f4-16cd4606582f)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
 truncate table student;
```
### OUTPUT:
![image](https://github.com/BharathCSEIOT/F2_DBMS/assets/122793480/7f54a5bc-cc97-467a-9255-4a5a298c598b)

### 5) Rename the student table to mystudent

### SQL QUERY: 
```
 ALTER TABLE student
  RENAME to mystudent;
```

### OUTPUT:
![image](https://github.com/BharathCSEIOT/F2_DBMS/assets/122793480/a9d3502e-33dd-48a4-b337-0417f0ff45ff)

### RESULT:
Hence successfully created a student database and execute DDL queries using SQL.
