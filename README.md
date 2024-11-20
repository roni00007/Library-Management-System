# Library Management System

## Introduction

This is a **Library Management System** developed in the C programming language. It is a console-based application designed to efficiently manage book records in a library. The program includes functionalities for adding, deleting, editing, searching, and issuing books.

---

## Features

1. **Main Menu**: Navigate through the program's functionalities using a simple menu system.
2. **Add Books**: Add new books to the library's catalog.
3. **Delete Books**: Remove books from the catalog by their unique ID.
4. **Edit Book Records**: Modify existing book records.
5. **Search Books**: Search for books by ID or name.
6. **Issue Books**: Issue books to students and track due dates.
7. **View Books**: Display the list of all available books in the library.
8. **View Issued Books**: View a list of books that have been issued along with their return dates.
9. **Secure Access**: Protected by a password for authorized use only.

---

## Getting Started

### Prerequisites
- Windows OS (required for Windows-specific headers like `windows.h`).
- A C compiler that supports ANSI C (e.g., GCC, Turbo C).

### Compilation and Execution
1. Save the source code into a file named `library.c`.
2. Open a terminal or command prompt.
3. Compile the code using the following command:
   ```
   gcc library.c -o library
   ```
4. Run the compiled program:
   ```
   library
   ```

---

## How to Use

1. **Login**:
   - The program begins with a password prompt.
   - Default password: `roni777`.
2. **Main Menu**:
   - After successful login, choose options by entering the corresponding number.
3. **Book Management**:
   - Add, delete, or edit book details.
   - Search for books by ID or name.
4. **Issue Management**:
   - Issue a book by providing its ID and student details.
   - View or remove issued books.

---


## Future Enhancements

- Add graphical user interface (GUI) support.
- Implement advanced search filters.
- Add a fine calculation feature for late returns.
- Support for multiple user roles (e.g., admin, librarian).

---

## Troubleshooting

- **Password Not Recognized**: Ensure the entered password matches `roni777`.
- **File Errors**: Ensure that the necessary data files (`lib.dat`, `Issue.dat`) are in the correct directory.

---

## Acknowledgments

This project is created as a **mini-project in C** for educational purposes. It demonstrates the use of file handling, struct-based data management, and basic console-based UI.

--- 
