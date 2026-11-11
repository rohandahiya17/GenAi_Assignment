Assignment -2 

This project demonstrates core Python concepts including conditional statements (if-elif-else), loop control (while, for, break, continue), exception handling (try-except), and list processing.

Tasks & Features

Task 1: Single Order Discount & Tax Calculation

Accepts user input for an order amount and validates it using try-except.
Calculates tiered discounts based on the order value.
Computes subtotal, applies a 5% tax rate, and outputs the final total amount.

Task 2: Multiple Orders Processing

Processes a predefined list of order amounts ([1200, 2500, 800, 1750, 3000]).
Iterates over each order to apply individual discount rules.
Tracks running total revenue and counts the number of orders receiving discounts.

Task 3: Interactive User Menu

Implements a CLI loop with options:
Add an order amount to a dynamic list.
View all stored orders with their applied discounts and final prices.
Quit (Q or q) to exit the program.
Uses continue to handle invalid menu choices and break to exit cleanly.

Task 4: Daily Sales Data Processing (Break & Continue)

Analyzes daily sales records: [200, 150, 0, 400, 50, -1, 300].
Uses loop control flow:
sale == 0: Skips processing (continue) to indicate no sales recorded.
sale < 0: Stops execution immediately (break) due to corrupted data.
sale > 0: Accumulates total sales revenue.