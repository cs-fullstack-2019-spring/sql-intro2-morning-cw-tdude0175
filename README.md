# SQL Intro Day 2 Morning Classwork

For this exercise you will create a ```Company``` Database that contains a single table called ```Employee```.

### Exercise 1:
* Create a new Postgres datasource
* Create a new database called ```Company```
* Create a new table in the database called ```Employee```

The ```Employee``` table should have the following fields:

```
Employee ID - Which should automatically increment for each new record added and should also be the primary key
Employee First Name
Employee Last Name
Employee Job Position 
Employee Salary
```

* Insert 4 new Employees using INSERT
```
Chuck, Jones, MANAGER, 100000
Marty, Krofft, ENGINEER, 80000
Peter, Barker, DEVELOPER, 50000
Sam, Sham, DEVELOPER, 35000
Ellen, Musk, DEVELOPER, 38000
```
* SELECT all Employee records from the database
* SELECT only the DEVELOPERS from the table
* SELECT only the Employees making more than 50000
* UPDATE the salary for Ellen Musk and give a raise to 42000
* DELETE  Sam Sham



