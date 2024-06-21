[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15309770&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   # Introduction to Python

   ## Python Basics

   **What is Python?**
   Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

   **Key Features:**
   - **Readable Syntax:** Python's syntax is clear and easy to read, which makes it accessible for beginners.
   - **Interpreted Language:** Python code is executed line by line, which simplifies debugging.
   - **Dynamically Typed:** Variable types are determined at runtime, making the language flexible.
   - **Large Standard Library:** Python has a comprehensive standard library that supports many tasks, from web development to data analysis.
   - **Community Support:** Python has a large and active community, providing a wealth of resources and libraries.

   **Use Cases:**
   - **Web Development:** Frameworks like Django and Flask.
   - **Data Science and Machine Learning:** Libraries such as NumPy, pandas, and TensorFlow.
   - **Automation and Scripting:** Automating repetitive tasks.
   - **Software Development:** Building desktop and server applications.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   ## Installing Python

   **Steps to Install Python on Windows:**
   1. **Download Python:**
      - Go to the [official Python website](https://www.python.org/downloads/) and download the latest version for Windows.
    2. **Run the Installer:**
      - Open the downloaded file and run the installer. Make sure to check the "Add Python to PATH" option.
    3. **Customize Installation:**
      - Customize the installation if needed, otherwise, proceed with the default settings.
    4. **Verify Installation:**
      - Open Command Prompt and type `python --version` to check if Python is installed correctly.

   **Setting Up a Virtual Environment:**
      1. **Create a Virtual Environment:**
      ```bash
      python -m venv myenv
      ```
    Activate the Virtual 
    Environment:
      ```bash
      myenv\Scripts\activate
      ```
    Deactivate the Virtual Environment:
      ```bash
      deactivate
      ```

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   ### Python Syntax and Semantics

   Create a file named `python_syntax_and_semantics.py`:

   ```python 
   # Python Syntax and Semantics

   # Simple Python Program
   print("Hello, World!")

   # Explanation:
   # - print: A built-in function that outputs a message to the console.
   # - "Hello, World!": A string literal enclosed in double quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   # Data Types and Variables

   # Basic Data Types
   # - Integer (int): Whole numbers, e.g., 42
   # - Float (float): Numbers with decimal points, e.g., 3.14
   # - String (str): Sequence of characters, e.g., "Hello"
   # - Boolean (bool): True or False values, e.g., True
   # - List (list): Ordered collection of items, e.g., [1, 2, 3]
   # - Dictionary (dict): Key-value pairs, e.g., {"key": "value"}

   # Variable Creation and Usage

   # Integer
   age = 30

   # Float
   pi = 3.14

   # String
   name = "Alice"

   # Boolean
   is_student = True

   # List
   numbers = [1, 2, 3]

   # Dictionary
   person = {"name": "Alice", "age": 30}

   # Print variables
   print("Integer:", age)         # Output: 30
   print("Float:", pi)            # Output: 3.14
   print("String:", name)         # Output: Alice
   print("Boolean:", is_student)  # Output: True
   print("List:", numbers)        # Output: [1, 2, 3]
   print("Dictionary:", person)   # Output: {'name': 'Alice', 'age': 30}

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
# Control Structures

# Conditional Statements
x = 10
if x > 0:
    print("x is positive")
    else:
    print("x is non-positive")

   # Loops

   # For loop
    for i in range(5):
    print(i)

   # While loop
    count = 0
    while count < 5:
    print(count)
    count += 1

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   # Functions in Python

   # Definition and Usage of Functions
   # - Definition: 
   Functions are reusable blocks of code that perform a specific task.

   # - Why Useful: 
   They help organize code, improve readability, and enable reuse.

   # Example Function
      def add(a, b):
       return a + b

   # Calling the function
       result = add(3, 5)
       print(result)  # Output: 8

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   # Lists and Dictionaries

   # Differences:

   **- Lists:**
   Ordered, indexed collections of items. Items are accessed by their index.
   **- Dictionaries:**
   Unordered collections of key-value pairs. Items are accessed by their key.

   # Example Script

   # List
   numbers = [1, 2, 3, 4, 5]
   print(numbers[2])  # Output: 3

   # Dictionary
   person = {"name": "Alice", "age": 30}
   print(person["name"])  # Output: Alice

   # Basic Operations
   numbers.append(6)
   person["city"] = "New York"
   print(numbers)
   print(person)

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
# Exception Handling

# What is Exception Handling?

Exception handling in Python is a mechanism to handle runtime errors, allowing the program to continue its execution.

# Example
try:
      x = 1 / 0
    except ZeroDivisionError:
      print("Cannot divide by zero")
   finally:
      print("This block always executes")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
# Modules and Packages:

**- Modules:** 
Single Python files containing definitions and statements.

**- Packages:**
 Collections of modules organized in directories.

# Importing and Using a Module
import math

# Using math module
print(math.sqrt(16))  # Output: 4.0


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    # File I/O

    # Reading from a File
    with open("example.txt", "r") as file:
   content = file.read()
   print(content)

    # Writing to a File
     lines = ["First line"
     "Second line", "Third line"]
    with open("output.txt", "w") as file:
    for line in lines:
    file.write(line + "\n")

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.

- Cite any references or sources you use in your answers.
# References
- [Python.org](https://www.python.org/)
- [Real Python](https://realpython.com/)
- [Python Virtual Environments: A Primer](https://realpython.com/python-virtual-environments-a-primer/)
- [Python Modules](https://docs.python.org/3/tutorial/modules.html)
- [Python Packages](https://realpython.com/python-modules-packages/)
- [Reading and Writing Files in Python](https://realpython.com/read-write-files-python/)

- Submit your completed assignment by [due date].


