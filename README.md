# Student Manager App

A simple console-based Student Manager application built using Python.
This project is beginner-friendly and demonstrates basic Python programming concepts
through a menu-driven application.

## Features

- Add a student with their name and marks
- View all added students
- Search for a student and check their result
- Display PASS or FAIL based on marks
- Exit the application through the menu

## Technologies Used

- Python

## Python Concepts Used

- Dictionary
- Variables and data types
- User input
- Conditional statements (if, elif, else)
- while loop
- for loop
- Dictionary methods (items())
- break statement
- Formatted strings (f-strings)

## How It Works

The application displays a menu with four options:

1. Add Student
2. View Student
3. Check Result
4. Exit

Student names and marks are stored in a Python dictionary.
A student is considered *PASS* if their marks are 40 or above.

## How to Run

1. Make sure Python is installed on your system.
2. Open the project folder in VS Code.
3. Run the following command in the terminal:

```bash
python student_result_manager.py
```

## Sample Output
```
---- STUDENT MANAGER APP -----

1. Add Student
2. View Student
3. Check Result
4. Exit

Enter your choice: 1
Enter student name: Sneha
Enter student marks: 85
Sneha Successfully Added!

----- STUDENT MANAGER APP -----

1. Add Student
2. View Student
3. Check Result
4. Exit

Enter your choice: 2
Sneha : 85

----- STUDENT MANAGER APP -----

1. Add Student
2. View Student
3. Check Result
4. Exit

Enter your choice: 3
Enter student name: Sneha
PASS
```

