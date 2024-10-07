

# Library Management System

## Project Overview

This is a basic and simple Library Management System developed, I developed using HTML and PHP, with a partner in Database Management System Lab, back in undergraduate studies. The system allows library authorities to manage books, users, and librarians by entering relevant information into temporary databases. It supports basic operations like update, delete, and display, as well as tracking books borrowed by users and managed by librarians.

### Group participants:
-Mahathir F Nabil
-Faria Afroz

---

## Features

- **Book Management**: Allows the librarian to enter, update, delete, and display book information.
- **User Management**: Facilitates the management of users who borrow books.
- **Borrowing System**: Tracks books borrowed by users.
- **Database Management**: Information on books, users, and librarians is stored in separate databases.

---

## Installation

1. Clone the repository:


$ git clone https://github.com/your-repo-url/library-management-system.git
$ cd library-management-system


2. Ensure you have PHP and MySQL installed on your system.

3. Create the database structure:

- Create a MySQL database and construct the required tables:
    - `book_info`
    - `user`
    - `borrowed`
    - `librarian`
    - `managed`

4. Launch the system by running a local PHP server:


$ php -S localhost:8000


5. Open your browser and navigate to `http://localhost:8000/index.php`.

---

## Database Structure

- **book_info**: Stores details about books (ISBN, title, author, edition, publication).
- **user**: Manages user information for the library system.
- **borrowed**: Tracks the borrowing activities of users.
- **librarian**: Handles librarian information.
- **managed**: Records books managed by the librarian.

---

## Technologies Used

- **HTML**: Defines the structure of the webpages.
- **PHP**: Handles server-side scripting and database operations.
- **MySQL**: Database used for storing and managing data.

---

## Code Highlights

### HTML Keywords

- `<html></html>`
- `<header></header>`
- `<center></center>`
- `<table></table>`
- `<tr></tr>`
- `<td></td>`

### PHP Syntax Examples

- `<?php ?>`
- `$query = "SELECT ISBN, TITLE, AUTHOR, EDITION, PUBLICATION FROM book_info WHERE TITLE LIKE '%$search%'";`
- `$result = mysqli_query($db, $query);`
- `<form action=" " method="POST">` / `<form action=" " method="GET">`
- `<input type="submit" value="Submit">`
- `<input type="reset" value="Reset">`

---

## Future Improvements

- **Enhance the UI/UX**: Improve the system's user interface for better user experience using frontend tools.
- **Add More Features**: Implement additional functionalities such as book reservations, overdue notices, and automated notifications.
- **Security Improvements**: Enhance the security of the system to prevent SQL injections and ensure secure data handling.

---

## References

- [Simple Library Management System PHP MySQL](https://krazytech.com/programs/simple-library-management-system-php-mysql)

---

Feel free to modify and enhance this README as the project evolves!
