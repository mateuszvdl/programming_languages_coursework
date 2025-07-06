# 🎓 My University Python Projects

This repository contains Python projects and exercises completed during my university coursework. It serves as both a learning portfolio and a way to track my progress in software development.

*Please note: These exercises were developed as part of my university studies in Poland, so the original comments, instructions, and some variable names are in Polish.*

---

## 📁 Projects

### 1. Intro to dicts and lists
* **File:** `intro_to_lists_and_dicts.ipynb`
* **Description:** This Jupyter Notebook contains my initial exercises exploring the fundamentals of Python. It's a hands-on introduction to core programming concepts.

#### Topics Covered:
* **Variables & Data Structures:** Lists, Dictionaries, and Tuples.
* **Control Flow:** Using `if`, `elif`, and `else` statements.

### 2. Functions in Python
* **File:** `functions.ipynb`
* **Description:** This notebook focuses on defining and using functions in Python, a core concept for writing clean and efficient code.

#### Topics Covered:
* **Function Basics:** Defining and calling functions.
* **Parameters:** Passing arguments, using default values, and keyword arguments.
* **Return Values:** Using the `return` statement to send data back from a function.

### 3. Control Flow Statements
* **File:** `control_flow.ipynb`
* **Description:** An in-depth exercise on control flow, covering conditional logic and loops to manage the execution path of a program.

#### Topics Covered:
* **Conditional Logic:** Advanced use of `if/else` statements.
* **Loops:** Iterating with `for` loops over different data types and using `while` loops for conditional execution.
* **Loop Control:** Using `break` to exit a loop.

### 4. Exception Handling
* **File:** `exception_handling.ipynb`
* **Description:** This notebook covers how to handle errors and exceptions in Python using `try...except` blocks to build more reliable applications.

#### Topics Covered:
* **Handling Errors:** Using `try` and `except` to prevent program crashes.
* **Specific Exceptions:** Catching specific errors like `ZeroDivisionError` and `ValueError`.
* **Custom Exceptions:** Defining and raising custom exception classes.

### 5. Mini-Projects: ATM and Number Game
* **File:** `mini_apps.ipynb`
* **Description:** This notebook combines previous concepts to build two small, interactive applications: a simple ATM simulator and a timed math game.

#### Topics Covered:
* **Application Structure:** Combining multiple functions to create a complete program.
* **State Management:** Using variables to manage state like login status and session activity.
* **User Interaction:** Building simple text-based menus and games.

### 6. Introduction to Object-Oriented Programming
* **File:** `object_oriented_programming.ipynb`
* **Description:** This project introduces the fundamentals of Object-Oriented Programming (OOP) by building a `Hero` class for a role-playing game.

#### Topics Covered:
* **Classes and Objects:** Defining a class and creating instances (objects).
* **Attributes:** Using the `__init__` method to define object properties.
* **Methods:** Creating functions within a class to define object behaviors.
* **Encapsulation:** Protecting data by using private attributes (`__`).

### 7. Advanced OOP with File I/O
* **File:** `oop_files.ipynb`
* **Description:** A project that builds on OOP concepts by integrating file I/O. It demonstrates how to create objects from data stored in an external JSON file, building a more realistic ATM application.

#### Topics Covered:
* **File I/O:** Reading from and writing to JSON files.
* **Object Hydration:** Creating class instances from file data.
* **Data Persistence:** Updating a JSON file with changes made during the program's execution.
* **Modular Design:** Structuring an application with multiple interacting classes (`Customer`, `Session`).

---

## ✅ How to Use

To run these projects on your local machine, you will need a tool that can open and execute Jupyter Notebooks (`.ipynb` files).

1.  **Clone the repository:**
    First, clone this repository to your local machine using the following command in your terminal.
    ```bash
    git clone [https://github.com/your-username/your-python-repo.git](https://github.com/your-username/your-python-repo.git)
    ```
    *(Remember to replace `your-username/your-python-repo.git` with the actual URL of your repository).*

2.  **Open the Notebooks:**
    Navigate into the cloned folder and open the `.ipynb` files in an application like **Jupyter Lab**, **Jupyter Notebook**, or **Visual Studio Code** (with the Python and Jupyter extensions installed).

3.  **Run the Code:**
    Once opened, you can run the code cells within each notebook to see the output and interact with the exercises.

4.  **Using the JSON File:**
    For the "Advanced OOP with File I/O" project (`exercise_8_oop_with_files.ipynb`), make sure the `customer_data.json` file is in the same directory as the notebook file. The script needs this file to load customer data.
