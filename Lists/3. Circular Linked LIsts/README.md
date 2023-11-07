# Circular Linked List

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Time and Space Complexity](#time-and-space-complexity)
- [Usage](#usage)
- [Example](#example)



## Overview

The Circular Linked List is a Python data structure that provides an efficient way to manage a list of elements where the last element is connected to the first element, creating a circular structure. This implementation offers various operations for inserting, updating, and removing elements, as well as iterating through the circular linked list.

## Features

- **Insertion**: You can insert elements at the end, the beginning, or a specific index.
- **Updating**: You can update elements at a specified index.
- **Removal**: You can remove elements from the beginning, end, or a specific index. Additionally, you can remove elements by their value.
- **Iteration**: The circular linked list supports iteration.

## Time and Space Complexity

Here are the time and space complexity details for each function in the Circular Linked List:

| Function                | Time Complexity           | Space Complexity     |
|-------------------------|---------------------------|----------------------|
| `insert_at_end(value)`  | O(1)                      | O(1)                 |
| `insert_at_beginning(value)` | O(1)               | O(1)                 |
| `insert_at_index(value, index)` | O(n)             | O(1)                 |
| `update_node(value, index)` | O(n)                   | O(1)                 |
| `remove_last_node()`    | O(n)                      | O(1)                 |
| `remove_first_node()`   | O(1)                      | O(1)                 |
| `remove_at_index(index)` | O(n)                     | O(1)                 |
| `remove_node(value)`    | O(n)                      | O(1)                 |
| `size_of_linked_list()` | O(1)                      | O(1)                 |
| `display()`             | O(n)                      | O(1)                 |
| `__iter__()`            | O(1)                      | O(1)                 |

## Usage

To use the Circular Linked List, you can create an instance of the `CircularLinkedList` class and then perform various operations on it as described in the API section.

## Example

Here's an example of how to use the Circular Linked List:

```python
# Create a circular linked list
my_linked_list = CircularLinkedList()

# Insert elements
my_linked_list.insert_at_end(10)
my_linked_list.insert_at_end(20)
my_linked_list.insert_at_end(30)

# Display the list
my_linked_list.display()

# Inserting a value at the beginning
my_linked_list.insert_at_beginning(5)

# Update a value at a specific index
my_linked_list.update_node(25, 2)

# Remove the first and last nodes
my_linked_list.remove_first_node()
my_linked_list.remove_last_node()

# Remove a node with a specific value
my_linked_list.remove_node(20)

# Insert a value at a specific index
my_linked_list.insert_at_index(15, 2)

# Remove a node at a specific index
my_linked_list.remove_at_index(2)

# Get the size of the circular linked list
size = my_linked_list.size_of_linked_list()


