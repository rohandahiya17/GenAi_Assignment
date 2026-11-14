Python Functions & Functional Programming AssignmentThis repository contains a Jupyter Notebook implementing seven foundational Python programming tasks. The exercises cover basic functions, recursion, lambda expressions, higher-order functions (map and filter), and a procedural CLI mini-project.

Overview of Tasks
Task 1: Basic Function (apply_discount)Description: Calculates the final price after applying a percentage discount.Features:Uses a default discount rate of 5% if none is provided.Caps the maximum allowable discount at 60%.
Task 2: Recursive Function (factorial_recursive)Description: Computes the factorial of a non-negative integer $n$ using recursion.Features:Handles base cases where $n = 0$ and $n = 1$ (returning 1).Validates input and returns an error message for negative numbers.
Task 3: Lambda Function (GST & After_Discount)Description: Uses anonymous lambda functions for quick financial calculations.Features:GST: Adds an 18% Goods and Services Tax to a given price.After_Discount: Computes adjusted pricing combining discount and tax factors.
Task 4: map() FunctionDescription: Applies the GST lambda function across an entire list of product prices ([100, 250, 400, 1200, 50, 2000, 850]) to generate a new list of tax-inclusive prices.
Task 5: filter() FunctionDescription: Segregates a list of prices into two distinct categories using filter() and lambda predicates:Expensive Products: Prices strictly greater than 500.Budget Products: Prices less than or equal to 500.
Task 6: Combined Utility Function (process_prices)Description: Combines map() and filter() inside a single reusable utility function.Workflow:Applies a 10% discount to all items in the input list.Filters the discounted items to return only those priced above 300.Returns both the full discounted list and the filtered list.
Task 7: Mini Project – Interactive Price ManagerDescription: A menu-driven Command-Line Interface (CLI) built strictly using loops and modular functions (no Object-Oriented Programming).Supported Operations:1 – Add a new price to the list (with ValueError exception handling).2 – Calculate and display the average price.3 – Find and display the maximum price.q – Quit the application.

 Prerequisites & Setup
 Python Version: Python 3.8+ (Tested on Python 3.13.17)Environment: Jupyter Notebook, JupyterLab, or VS Code with the Jupyter extension.
 
 Running the Notebook
 Clone or download this repository to your local machine.Open your terminal and navigate to the project directory.Launch Jupyter Notebook:jupyter notebook
Open the .ipynb file and run the cells sequentially (Shift + Enter).