Assignment - 1 

This Jupyter Notebook project demonstrates fundamental Python data structures (Lists, Tuples, Sets, and Dictionaries).
 
Overview 

The assignment covers practical usage of core Python collection types through a step-by-step implementation of product indexing, categorization, price calculations, and data aggregation.

Key concept areas covered:

Indexing, appending, and immutability handling (Lists vs. Tuples).

Set operations, uniqueness checking, and fast lookup.

Dictionary mutations, value aggregation, and key sorting.

Combining collections using zip(), list comprehensions, and dictionary grouping.

Tasks & Implementation Details

Task 1: Product Collections (Lists & Tuples)

Concepts: Basic list operations and tuple immutability.

Key Steps:

Accessing elements using positive and negative indexing (Products[1], Products[-1]).

Appending new items to a list.

Mutating a tuple by converting it to a list, updating values, and casting it back to a tuple.

Task 2: Categories (Sets)

Concepts: Uniqueness, set modification, and membership verification.

Key Steps:

Converting a product category list into a set to extract unique values.

Adding new entries to a set (add()).

Checking if a category exists via user input (in keyword).

Calculating the total count of unique categories using len().

Task 3: Product Pricing (Dictionaries)

Concepts: Key-value mapping, updates, deletions, and min/max key extraction.

Key Steps:

Initializing a price dictionary, updating existing keys, adding new products, and removing keys (del).

Calculating the average product price using sum() and len().

Finding the most and least expensive products using max() and min() with key functions (key=price_dict.get).

Task 4: Combined Operations

Concepts: Data merging, filtering, and structural aggregation.

Key Steps:

Pairing product names and categories together using zip().

Constructing a unified Catalog list of tuples (name, price, category) using list comprehensions and checking key existence.

Grouping products by category into a dictionary (category_to_products) using .setdefault().

Identifying the category containing the highest number of products using max() with a lambda expression.
