Java Library Management System (GUI + MySQL)

This is a desktop Library Management System built using Java Swing and MySQL. It is designed to help librarians manage books and members, and to keep track of borrowing and returning activities through an easy-to-use graphical interface.

Key Features

- Add and manage books with details such as title, author, ISBN, genre, and current availability.
- Register and view library members along with their basic information (name and email).
- Search for books by title, author, or genre directly from the Member section.
- Issue and return books, with a record of each member’s transaction history.
- Automatically update a book’s availability status when it is issued or returned.
- Login screen with user authentication using a `users` table (supports admin/librarian login).
- Integration with MySQL using JDBC, `PreparedStatement`, and transaction handling.
- Uses `SwingWorker` to load data in the background so the UI stays responsive.
- Modern look and feel with FlatLaf, titled borders, and an improved layout.
- Simple dashboard displaying quick stats such as total books, available books, and issued books.

Technology Stack

- Java (Swing)
- MySQL
- JDBC (MySQL Connector/J)
- FlatLaf look and feel for the UI

How to Run the Project

1. Open/import the project in IntelliJ IDEA.
2. Create a MySQL database named `library_db` and execute the provided SQL scripts to create the required tables.
3. Adjust the database username and password in `DBConnection.java` according to your local MySQL setup.
4. Build and run the `main` class.
5. Log in using the default credentials:
   - Username: `admin`
   - Password: `admin123`
