# Library Management System

A simple **Python Library Management System** built using basic Python concepts such as lists, functions, conditionals, loops, user input, and list operations.

## Features

The program provides a menu-driven interface with the following options:

1. **Add a Book** – Adds a new book to the library.
2. **Show Available Books** – Displays all books currently available.
3. **Borrow a Book** – Removes a book from the available list and places it in the borrowed list.
4. **Return a Book** – Returns a borrowed book to the available list.
5. **Quit** – Exits the program.

## Technologies Used

- Python 3
- Lists
- Functions
- `if / elif / else`
- `while` loop
- `for` loop
- `input()` and `print()`
- `append()` and `remove()`
- `enumerate()`

## Project Structure

```text
library-management-system/
│
├── library_management_system.py
├── README.md
├── statement.md
├── .gitignore
└── screenshots/
    ├── library_output_1.jpg
    ├── library_code_1.jpg
    └── library_code_2.jpg
```

## How the Program Works

The program maintains two lists:

- `books` – contains books currently available in the library.
- `taken` – contains books that have been borrowed.

When a user borrows a book, the program removes it from `books` and adds it to `taken`.

When a user returns a book, the program removes it from `taken` and adds it back to `books`.

Book names entered by the user are converted to uppercase so that book-name matching is consistent.

## How to Run

### 1. Install Python

Make sure Python 3 is installed on your computer.

Check your Python version:

```bash
python --version
```

### 2. Run the program

Open a terminal in the project folder and run:

```bash
python library_management_system.py
```

On some systems, you may need:

```bash
python3 library_management_system.py
```

## Example Menu

```text
LIBRARY MANAGEMENT SYSTEM
 Library's menu
1. Add A Book
2. Show Available Books
3. Borrow A Book
4. Return A Book
5. Quit
Choose any option number(1-5):
```

## Sample Operations

### Add a Book

Choose `1` and enter a book name.

```text
Enter the name of the book to add: Python Basics
PYTHON BASICS has been added.
```

### Show Available Books

Choose `2` to display the books currently available.

### Borrow a Book

Choose `3` and enter the name of an available book.

If the book exists, it is moved to the borrowed list.

### Return a Book

Choose `4` and enter the name of a borrowed book.

If the book was borrowed, it is moved back to the available list.

## Notes

- This project uses in-memory lists, so changes are not permanently saved after the program closes.
- The program does not use an external database.
- Book names are converted to uppercase before being stored or searched.
- The project is intended as a beginner-level Python project demonstrating basic programming concepts.

## Author

**Albert Joseph**

## License

This project is provided for educational purposes.
