# BookTracker

## Introduction
BookTracker is a command-line application that allows users to manage and analyze reading habits data. The application interacts with an SQLite database using Java and JDBC to provide various functionalities related to user and book data management.

## Features
The application provides the following functionalities:
1. **Add a user**: Insert a new user into the database.
2. **Retrieve user reading data**: Fetch all reading habit data for a specified user.
3. **Change book title**: Update the title of a book in the database.
4. **Delete a reading habit record**: Remove a specific record from the ReadingHabit table.
5. **Calculate mean age of users**: Retrieve the average age of all users.
6. **Find total readers of a book**: Get the number of users who have read pages from a specific book.
7. **Compute total pages read**: Sum up the total pages read by all users.
8. **Count users who read multiple books**: Determine the number of users who have read more than one book.
9. **Add a 'Name' column to User table**: Modify the database schema to include a 'Name' column.

## Requirements
- Java (JDK 8 or higher)
- SQLite
- JDBC (Java Database Connectivity)
- Git (optional, for version control)


## Database Setup
1. Ensure SQLite is installed.
2. Load the provided dataset into the SQLite database.
3. Use the `schema.sql` file to create the necessary tables.
4. Connect the application to the SQLite database using JDBC.



## Author
- Umayma Ahmed


