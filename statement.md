# Project Statement

## Project Title

**Library Management System**

## Problem Statement

Managing books manually can become difficult when the number of books increases. A simple computer-based system can make basic library operations easier by keeping track of which books are available and which books have been borrowed.

The objective of this project is to develop a **menu-driven Library Management System in Python** that allows a user to add books, view available books, borrow books, return books, and exit the program.

## Objectives

The main objectives of the project are:

- To create a simple library management program using Python.
- To maintain a list of available books.
- To maintain a list of borrowed books.
- To allow users to add new books.
- To display the books currently available.
- To allow users to borrow available books.
- To allow users to return borrowed books.
- To practice Python functions, lists, loops, conditions, and user input.

## Functional Requirements

### 1. Add a Book

The system should allow the user to enter the name of a new book and add it to the available books list.

### 2. Show Available Books

The system should display all books currently available in the library with their corresponding numbers.

### 3. Borrow a Book

The system should allow the user to enter the name of a book. If the book is available, it should be removed from the available books list and added to the borrowed books list.

If the requested book is not available, the system should display an appropriate message.

### 4. Return a Book

The system should allow the user to enter the name of a book they want to return. If the book exists in the borrowed books list, it should be removed from that list and added back to the available books list.

### 5. Exit

The system should allow the user to quit the program.

## Data Used

The program uses two main Python lists:

```python
books = [...]
taken = []
```

- `books` stores available books.
- `taken` stores borrowed books.

## Program Flow

```text
Start
  |
  v
Display Library Menu
  |
  +----> 1. Add Book ----------> Add book to available list
  |
  +----> 2. Show Books ---------> Display available books
  |
  +----> 3. Borrow Book --------> Move book from books to taken
  |
  +----> 4. Return Book --------> Move book from taken to books
  |
  +----> 5. Quit ---------------> End Program
  |
  +----> Invalid Option --------> Display error and show menu again
```

## Python Concepts Demonstrated

The project demonstrates:

- Variables
- Lists
- Functions
- Function calls
- `input()`
- `print()`
- `if`, `elif`, and `else`
- `while True`
- `for` loops
- `enumerate()`
- `append()`
- `remove()`
- Membership checking using `in`
- String conversion using `.upper()`
- `break`

## Expected Outcome

After running the program, the user should be able to interact with the library through the menu and perform the supported operations without needing to modify the source code.

The program should correctly move books between the available and borrowed lists when books are borrowed or returned.

## Limitations

The current version has a few limitations:

- Data is stored only in memory.
- Books are not saved to a file or database.
- There is no user/login system.
- There is no due-date or fine calculation.
- The system does not maintain individual borrower information.

## Future Scope

The project can be expanded by adding:

- File or database storage.
- User accounts and authentication.
- Borrower information.
- Due dates and fine calculation.
- Search functionality.
- Book categories and authors.
- Duplicate-book validation.
- A graphical user interface.
- A web-based interface.

## Conclusion

The Library Management System provides a simple way to perform basic library operations using Python. It demonstrates fundamental programming concepts and provides a foundation that can be extended into a more advanced library management application.
