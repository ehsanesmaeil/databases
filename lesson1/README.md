# Lesson 1: Retrieving Data

In this class, students will be introduced to relational data terminology (row, column), the function of a primary key, and retrieving data from a MySQL database using SELECT queries.

Objective: Students should be able to retrieve data from a database table using SELECT statements that include WHERE, GROUP BY, and ORDER BY.

## Pre-Class Preparation

Before the class you should install MySQL on your computer:
- Instructions for macOS: [click here](https://www.youtube.com/watch?v=7S_tz1z_5bA&t=290s)
- Instructions for Windows: [click here](https://www.youtube.com/watch?v=7S_tz1z_5bA&t=588s)

## Main Topics

- The relational model of data
- A 'database' vs. a 'DBMS' (database management system)
- The concept of a schema
- The properties of an 'entity' (or 'row')
- Basic entity relationship diagrams
- A basic SELECT statement
- Constructing more complex SELECT statements
- Pattern matching with LIKE
- Limiting and ordering results with LIMIT and ORDER BY
- Grouping results with GROUP BY
- Aggregate functions like AVG, COUNT, SUM, MIN and MAX
- JOIN
    - Selecting composite data from multiple tables
    - Compare JOIN WHERE with cartesian product
- Naming Conventions: UpperCamelCase/PascalCase, lowerCamelCase, snake_case, hnHungarianNotation/HNHungarianNotation
- Character Sets in Databases (hint: always use UTF-8 encoding, called 'utf8mb4' in MySQL)


## Reference Material

- [TutorialsPoint MySQL Introduction](http://www.tutorialspoint.com/mysql/mysql-introduction.htm)
- [w3schools tutorial (easy to find how specific commands work)](https://www.w3schools.com/sql/default.asp)
- [Official MySQL Documentation](https://dev.mysql.com/doc/refman/8.0/en/)
- [Official MySQL Tutorial (pretty dense)](https://dev.mysql.com/doc/refman/8.0/en/tutorial.html)
- [Joel Spolsky - Character Sets and Unicode](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

## Homework

Design queries that retrieve the following data sets. Compare with classmates to see if your answers are correct.

1. Find out how many tasks are in the task table
2. Find out how many tasks in the task table do not have a valid due date
3. Find all the tasks that are marked as done
4. Find all the tasks that are not marked as done
5. Get all the tasks, sorted with the most recently created first
6. Get the single most recently created task
7. Get the title and due date of all tasks where the title or description contains **database**
8. Get the title and status (as text) of all tasks
9. Get the name of each status, along with a count of how many tasks have that status
10. Get the names of all statuses, sorted by the status with most tasks first


Watch the previous session recorded on video here:

Part 1 : https://www.youtube.com/watch?v=gAeww1z5774

Part 2 : https://www.youtube.com/watch?v=u77w6Lw2gOY

Part 3 : https://www.youtube.com/watch?v=Mag9n6olmRU
