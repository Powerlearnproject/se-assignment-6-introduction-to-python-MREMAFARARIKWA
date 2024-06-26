[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15328880&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.


--Python is a high-level, interpreted programming language known for its extensive starndard library, crosss platform compatibility, simplicity, readability, and versatility. 

---Some key features that make Python popular among developers include:
-- Easy to learn and use
-- High-level syntax and abstractions
-- Interpreted language (no compilation needed)
-- Dynamic typing
-- Large standard library and ecosystem (e.g., NumPy, pandas, Django)
-- Cross-platform compatibility
-- Extensive community and resources

---Examples of use cases where Python is particularly effective:
  --Web Development; frameworks like Django and Flask allow web app development
  -- Data analysis and visualization: Analyzing and visualizing large datasets with libraries like pandas, Matplotlib, and Seaborn.
  -- Web scraping and crawling: Using libraries like BeautifulSoup and Scrapy to extract data from websites.
  -- Automation of tasks: Automating tasks with scripts using libraries like os, sys, and subprocess.
  -- Scientific simulations: Performing numerical simulations with libraries like NumPy and SciPy.
  -- Machine learning and AI: Building AI and ML models with libraries like scikit-learn, TensorFlow, and Keras.
  --Game development; pygame and other other libraries  enables game development 
  --Desktop applications; tools likePyQtand Tkinter make cross platforn desktop applications


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

 ---- Steps to Install Python on windows---

 -- Go to the official Python download page
 --Click on the appropriate link for Windows.
 -- Select the desired version e.g Python 3.12.4
  --Download the installer file
 -- Run the downloaded installer 
-- Follow the prompts to install Python.
-- Choose the installation location
--Select the option to add Python to your PATH 

--- Verifing the Installation---
--Open a Command Prompt or PowerShell
-- Type python --version and press Enter
-- You should see the version of Python you just installed e.g Python 3.12.4

---Setting up a Virtual Environment---

-- Open a Command line interface or PowerShell.
-- Install the virtualenv package by running python -m pip install virtualenv
-- Create a new virtual environment by  python -m virtualenv (envname)
-- Activate the virtual environment by running (envname)\Scripts\activate 



3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

Python

print("Hello, World!")

--print() function is a built-in function is used to display its argument in the console.  it takes one or more arguments
--string: The text enclosed in double quotes ("Hello, World!") is a string. Strings are sequences of characters and can be used to represent text data.
--()parentesis, which are used to enclose arguments for a function


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   ---Basic data types in Pytyhon---
--Integer (int):
Represents positive or negative whole numbers without any decimal point.
Example: 2, -6, 9870

--Float (float):
Represents real numbers (numbers with a decimal point).
Example: 4.84, 9.71828, 

--String (str):
Represents a sequence of characters enclosed within single quotes (') or double quotes (").
Example: "greeting", 'word', "675"

--Boolean (bool):
Represents one of two values: True or False.
Used for logical operations and conditions.
Example: True, False
--List (list):
Represents an ordered collection of items enclosed within square brackets 
Items in a list can be of different data types and can be changed (mutable).
Example: [1, 2, 3, 4], ['apple', 'banana', 'cherry']

--Tuple (tuple):
Similar to lists, but enclosed within parentheses (()).
Items in a tuple can be of different data types, but tuples are immutable (cannot be changed after creation).
Example: (1, 2, 3), ('a', 'b', 'c')

--Dictionary (dict):
Represents a collection of key-value pairs enclosed within curly braces ({}).
Each key-value pair maps the key to its corresponding value.
Example: {'name': 'Alice', 'age': 78, 'town': ' South Africa}

 ---Using Variables---
--Integer variable
age = 25
print("Age:", age)  Output- 25
---Float variable
li = 3.14
print("li:", li)  Output- 3.14
---String variable
name = "Alice"
print("Name:", name)  -output- Alice
--- Boolean variable
is_student = True
print("Is student:", is_student)  output: True
---List variable
fruits = ['apple', 'banana', 'cherry']
print("Fruits:", fruits)  Output ['apple', 'banana', 'cherry']
---Tuple variable
relation = (15, 30)
print("Relation:", relation)  # Output: (15, 30)
---Dictionary variable
person = {'name': 'Bob', 'age': 30, 'city': 'London'}
print("Person:", person)   {'name': 'Bob', 'age': 30, 'city': 'London'}


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

 ---Conditional statements and loops are fundamental concepts in programming,. They allow you to control the flow of your program based on certain conditions or repeat a block of code multiple times.
            
            ---'if-else'---
-- x = 100
if x < 75:
    print("x is smaller than 75")
else:
    print("x is greater than or equal to 75")
-- Output: x is greater than or equal to 75

    ---'for'---
fruits = ["peach", "mango", "papaya"]
for fruit in fruits:
    print(fruit)
 Output: peach, mango, papaya



6. Functions in Python:

   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   ----In Python, a function is a reusable block of code that performs a specific task. Functions allow you to organize your code in manageable pieces, make it more modular, and avoid repetition. 

      ---key notes---
---Definition: You define a function using the def keyword, followed by the function name and a set of parentheses. ---Inside the parentheses, you can specify parameters (also known as arguments) that the function accept      ---Calling a Function: To use a function, you call it by its name followed by parentheses. This executes the code within the function.

---Parameters and Arguments---
---Parameters: These are the variables listed inside the parentheses in the function definition. They act as placeholders for the values you pass when calling the function.
---Arguments: These are the actual values provided when calling the function.
---Return Values: A function can return data as a result using the return statement to specify what value the function should produce.

--- Python function that takes two arguments and returns their sum:

Python
def add_numbers(a, b):
    return a + b

This function has:
- Name: add_numbers
- Parameters: a and b
- Body: return a + b

----calling the function----  
result = add_numbers(3, 5)
print(result)   Output 8

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations for both.
   
    ---Differences between lists and dictionaries---
--Order-- Lists are ordered, while dictionaries are unordered.
--Access -- Lists are accessed by index, whereas dictionaries are accessed by keys.
--Purpose-- Lists are used when the collection of items needs to be ordered and accessed by position. Dictionaries are used when data is stored and accessed via keys for quick lookup.
--Elements--  Lists can contain any data type including lists themselves, whereas dictionary values can be any Python object including other dictionaries

---Scripts---

--- Create a list of numbers
numbers = [1, 2, 3, 4, 5]
print(numbers)  # [1, 2, 3, 4, 5]

basic operations--- 
print(numbers[0])  # 1 (accessing the first element)
numbers.append(6)  # adding an element to the end
print(numbers)  # [1, 2, 3, 4, 5, 6]
numbers.sort()  # sorting the list
print(numbers)  # [1, 2, 3, 4, 5, 6]


--- Create a dictionary with key-value pairs
person = {"name": "John", "age": 30, "city": "New York"}
print(person)  # {"name": "John", "age": 30, "city": "New York#'}

 Basic operations for dictionaries---
print(person["name"])  # John (accessing a value by key)
person["country"] = "USA"  # adding a new key-value pair
print(person)  # {"name": "John", "age": 30, "city": "New York", "country": "USA"}
del person["age"]  # deleting a key-value pair
print(person)  # {"name": "John", "city": "New York", "country": "USA"}



8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   ---Exception handling in Python is a way to manage errors and exceptions that may occur during the execution of a program. It allows you to developer to handle runtime errors, preventing  program from crashing and providing a better user experience.

- try: The code that might raise an exception is placed in the try block.
- except: The code that handles the exception is placed in the except block. You can specify the type of exception to catch.
- finally: The code in the finally block is executed regardless of whether an exception occurred or not.

    Example---

try:
    # Code that might raise an exception
    x = 1 / 0
except- ZeroDivisionError:
    # Handle the exception
    print("Cannot divide by zero!")
finally:
    # Code that runs regardless of the exception
    print("Program continues...")

-- The try block attempts to divide by zero, which raises a ZeroDivisionError.
-- The except block catches the exception and prints an error message.
-- The finally block runs regardless of the exception and prints a message indicating that the program continues.


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   In Python, modules and packages are ways to organize and reuse code.

Modules:

- A module is a single file with a .py extension that contains Python code.
- Modules can contain functions, classes, variables, and other definitions.
- Modules can be imported into other Python scripts to reuse their code.

Packages:

- A package is a directory with a __init__.py file that contains multiple modules.
- Packages can contain sub-packages and modules.
- Packages can be imported like modules, allowing access to their contents.

---to import a module , we use the import statement follwed by the module name  without the .py extension 
eg. import math

----Then you get the module's contents using the dot notation eg.

result = math.ceil(3.14)
print (result)
output 4


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    
---In Python, you can read from and write to files using the built-in open() function.

Reading from a file script---

file = open("filename.txt", "r")  -- Open the file in read mode (r)
content = file.read()  -- Read the entire file content
print(content)  -- Print the content to the console
file.close() -- Close the file

Writing to a file  script---

file = open("filename.txt", "w")   Open the file in write mode (w)
data = ["Hello", "World", "Python"]  -- List of strings to write
for line in data:
    file.write(line + "\n")  -- Write each string to the file
file.close()  --Close the file





# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


