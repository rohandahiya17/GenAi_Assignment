Python File Handling Assignment :-
This repository contains solutions for a 7-task Python File Handling assignment, demonstrating how to create, read, append, process, and safely handle text files without external libraries.

Repository Contents
File_Handling.ipynb : Jupyter Notebook containing the Python code and outputs for all 7 tasks.
sales_data.txt      : Generated text file storing sales records line-by-line (including appended records).sales_data_comma.txt: Generated text file storing initial sales records in comma-separated format.
product.txt         : Generated text file storing user-inputted product names and prices.
discount_report.txt : Generated report displaying original and discounted prices for a product catalog.


Tasks Overview

Task 1: Write Sales Records to a File
Writes a list of initial sales amounts ([1200, 450, 980, 1500, 3000]) line-by-line into sales_data.txt.
Extra: Writes the same sales data in a comma-separated format into sales_data_comma.txt.

Task 2: Read File in Different Ways
Reads and prints the entire content of sales_data.txt using .read().
Reads and prints the first line using .readline().
Reads all lines using .readlines(), strips newline characters (\n), and converts the values into a list of integers.

Task 3: Append New Sales
Appends new sales figures ([1500, 2500, 1700]) to sales_data.txt using append mode ("a").
Extra: Counts and displays the total number of lines in the updated file (8 lines).

Task 4: Generate Summary Report from File
Reads all integer sales values from sales_data.txt and computes key metrics using built-in Python functions:
Total Sales:12830
Highest Sale:3000
Lowest Sale:450
Average Sale:1603.75

Task 5: Create Product Info File (User Input)
Prompts the user to enter 3 product names and their prices.
Saves the entries into product.txt formatted as ProductName | Price and reads back the file contents.

Task 6: Read File Safely
Prompts the user for a filename to open (product.txt, sales_data.txt, or sales_data_comma.txt).
Safely reads and displays the file if valid, or prints "File not found. Please check the file name." if invalid.

Task 7: Mini Project - Export Discounted Prices
Takes a dictionary of electronics items and asks the user for a discount percentage.
Calculates the discounted price for each item and exports a formatted table (Product | Original Price | Discounted Price) to discount_report.txt.
Extra: Calculates and displays the total number of items (5) and the average discounted price.

How to Run
Ensure you have Python 3.x and Jupyter Notebook (or VS Code with the Jupyter extension) installed.
Clone or download this repository to your local machine.
Open "File_Handling.ipynb" and run the cells sequentially from Task 1 to Task 7 (running them in order ensures the text files are created before subsequent tasks read or append to them).