# DBMS Using Bash Script

This project aims to develop a **Database Management System (DBMS)** that allows users to efficiently store, manage, and retrieve data locally. The system provides a simple interface for interacting with the stored data, simulating the basic operations of a traditional DBMS.

- **Database Management**: The system will allow users to create, list, connect to, and drop databases.
- **Table Management**: Once connected to a database, users can create tables, list tables, drop tables, and perform CRUD operations.
- **Data Handling**: Users can insert, update, delete, and select data from tables, with support for specifying column types and enforcing primary key constraints.

## Key Features

### Main Menu
- **Create Database**: Create a new database, which will be stored as a directory in the current script's directory.
- **List Databases**: List all available databases.
- **Connect to Database**: Allows users to connect to a specific database, transitioning to the database-specific menu.
- **Drop Database**: Deletes a specific database.

### Database-Specific Menu (After Connecting to a Database)
- **Create Table**: Create a table by specifying columns and their data types.
- **List Tables**: List all tables within the connected database.
- **Drop Table**: Delete a specific table within the connected database.
- **Insert into Table**: Insert data into a specified table, with checks for column data types and primary key constraints.
- **Select from Table**: Query and display data from a table in a formatted manner.
- **Delete from Table**: Remove records from a table.
- **Update Table**: Modify data in a table with proper checks on data types.

## Installation

To run this project, follow these steps:

1. Clone the repository or download the files to your local machine.

2. Open your terminal and navigate to the folder containing the project files.

3. Start the project by executing the `main_menu` script.
  

