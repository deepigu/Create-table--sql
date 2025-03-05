# SQL Create Table Statements

This project provides SQL `CREATE TABLE` statements for a relational database schema designed to manage information about instructors, courses, students, assignments, tasks, and their interrelationships.

## Database Schema

The database schema consists of the following tables:

1. **Instructor**
   - **Columns:**
     - `email`: The primary key representing the instructor's email address.
     - `affiliation`: The institution or organization the instructor is affiliated with.
     - `name`: The full name of the instructor.

   ```sql
   CREATE TABLE instructor (
       email VARCHAR(255) NOT NULL,
       affiliation VARCHAR(255) NOT NULL,
       name VARCHAR(255) NOT NULL,
       PRIMARY KEY (email)
   );
