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
create table studentss(rollno int,name varchar(20),age int,address varchar(20),phoneno int);
```
### OUTPUT:
![11](https://github.com/varshxnx/G2_DBMS/assets/122253525/8d13abff-7822-48db-8ac9-fc47d2aaf346)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table studentss ADD department varchar(30);
```
### OUTPUT:
![12](https://github.com/varshxnx/G2_DBMS/assets/122253525/82a4ba24-0307-4c42-b833-9a1c35853453)



### 3) Drop the student table
 
### SQL QUERY: 
```
drop table mystudent;

```
### OUTPUT:
![13](https://github.com/varshxnx/G2_DBMS/assets/122253525/f1973af5-a3aa-4ff1-937a-c82782b03704)



### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table mystudent;

```
### OUTPUT:
![14](https://github.com/varshxnx/G2_DBMS/assets/122253525/53ece79a-e8e1-4b01-8180-ed627069ddb3)


### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;

```
### OUTPUT:
![15](https://github.com/varshxnx/G2_DBMS/assets/122253525/ff08cde9-1bdc-4450-bb63-9029a22088f3)


### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
