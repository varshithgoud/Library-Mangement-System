# Library Management System (LMS)

This is a simple Library Management System (LMS) implemented in Java and MySQL. The system allows librarians to manage books, borrowers, and borrowing transactions.

## Prerequisites

To run the LMS, you need to have the following software installed on your system:

- Java Development Kit (JDK) 8 or later
- MySQL Server

## Setup

1. Clone the repository or download the source code.

2. Import the SQL dump file `lmsdump.sql` into your MySQL server to create the database and tables.

    a. Open Intellij Add the MySQL Connector/J library to lms project:

    b. Download the MySQL Connector/J library from the MySQL website (https://dev.mysql.com/downloads/connector/j/).

    c. Extract the downloaded ZIP file to a location on your computer.

    d. In IntelliJ IDEA, `Open the Project Structure` from main menu.

    e. Choose `Library` from the Project Settings.

    f. Click on `+` and choose the Jar\MySQL Connector extract file.

    g. Click on `apply` then `OK` to add the library to your project.
    
3. Open the `DatabaseConnection.java` file and modify the `URL`, `USERNAME`, and `PASSWORD` variables with your MySQL connection details.

4. Compile the Java source files using the following command: `javac *.java`

## Running the Application

After compiling the source files, you can run the application with the following command: `java Main`

This will start the Library Management System application and display a menu-driven interface in the console.

## Usage

The application provides the following functionalities:

1. **Add Book**: Allows librarians to add new books to the system.
2. **Add Borrower**: Allows librarians to add new borrowers to the system.
3. **Borrow Book**: Allows librarians to process borrowing transactions.
4. **Return Book**: Allows librarians to process book return transactions.
5. **Search Books**: Allows users to search for books based on various criteria.
6. **View Borrowing History**: Allows users to view the borrowing history of a specific borrower.

Follow the on-screen instructions to navigate through the menu and perform the desired operations.

## Documentation

A separate documentation file (`LibraryManagmentSystem.docx`) is provided, which includes screenshots for each implemented functionality.

## Note

Make sure to have the required software installed and configured correctly before running the application.