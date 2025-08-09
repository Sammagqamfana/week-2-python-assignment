# List Operations in Python

This Python script demonstrates basic list operations including appending, inserting, extending, removing, sorting, and searching within a list.

## Features

- Create an empty list and append elements to it.
- Insert an element at a specific position.
- Extend the list with multiple elements.
- Remove the last element from the list.
- Sort the list in ascending order.
- Find the index of a specific value in the list.

## Code Overview

```python
my_list = []
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
print(my_list)

my_list.insert(1, 15)  # Insert 15 at the second position
my_list.extend([50, 60, 70])  # Extend list with multiple values
my_list.pop()  # Remove the last element
my_list.sort()  # Sort the list in ascending order

index_of_30 = my_list.index(30)  # Find index of value 30
print("Index of 30:", index_of_30)
