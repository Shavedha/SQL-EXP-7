# SQL - EXPERIMENT 7 - To create a database table, insert the values, display the table and to perform the Operations, SUM(), COUNT(), AVG()
## AIM
To  
1. Create a database 
2. create a table 
3. Insert the values 
4. Display the table 
and to perform the Operations: SUM(), COUNT(), AVG()

## ALGORITHM 
1. Create a table and insert values using keywords "create table","insert into values". 
2. Display the table using "select" 
3. Using sum() , count() and avg() perform the operations. 
4. Display the result.

## PROGRAM
```
-- create
CREATE TABLE STUDENT (
  sid INTEGER PRIMARY KEY,
  sname TEXT NOT NULL,
  smark TEXT NOT NULL
);

-- insert
INSERT INTO STUDENT VALUES (0001, 'Clark',83);
INSERT INTO STUDENT VALUES (0002, 'Dave',67);
INSERT INTO STUDENT VALUES (0003, 'Ava', 92);
INSERT INTO STUDENT VALUES (0004, 'Tom', 78);
INSERT INTO STUDENT VALUES (0005, 'Ava', 59);

-- fetch 
SELECT * FROM STUDENT ;

SELECT SUM(smark) "SUM : " FROM STUDENT;
SELECT count(*) "Count : "FROM STUDENT;
SELECT avg(smark) "Average : "FROM STUDENT;
```

## OUTPUT
<img width="261" alt="image" src="https://github.com/Shavedha/SQL-EXP-7/assets/93427376/ecace582-d63f-43a4-8e37-c5b783ae8772">

## RESULT
Hence the program has been successfully executed.
