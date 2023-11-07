# MyLinkedList Class

The `MyLinkedList` class is an implementation of a singly linked list in Python. It provides various methods to manipulate the linked list, including appending, inserting at the beginning or a specific index, updating nodes, and removing nodes.

## Methods

- `append(value)`: Add a value to the end of the linked list.
- `insert_at_beginning(value)`: Insert a value at the beginning of the linked list.
- `insert_at_index(value, index)`: Insert a value at a specific index in the linked list.
- `insert_at_end(value)`: Insert a value at the end of the linked list.
- `update_node(value, index)`: Update the value of a node at a specific index.
- `remove_first_node()`: Remove the first node in the linked list.
- `remove_last_node()`: Remove the last node in the linked list.
- `remove_at_index(index)`: Remove a node at a specific index.
- `remove_node(value)`: Remove a node with a specific value.
- `size_of_linked_list()`: Get the size (number of nodes) of the linked list.
- `display()`: Display the elements of the linked list.

## Time and Space Complexity Analysis

- `__init__(self)`
  - **Time Complexity:** O(1)
  - **Space Complexity:** O(1)

- `append(self, value)`
  - **Time Complexity:** O(n)
  - **Space Complexity:** O(1)

- `insert_at_beginning(self, value)`
  - **Time Complexity:** O(1)
  - **Space Complexity:** O(1)

- `insert_at_index(self, value, index)`
  - **Time Complexity:** O(n)
  - **Space Complexity:** O(1)

- `insert_at_end(self, value)`
  - **Time Complexity:** O(n)
  - **Space Complexity:** O(1)

- `update_node(self, value, index)`
  - **Time Complexity:** O(n)
  - **Space Complexity:** O(1)

- `remove_first_node(self)`
  - **Time Complexity:** O(1)
  - **Space Complexity:** O(1)

- `remove_last_node(self)`
  - **Time Complexity:** O(n)
  - **Space Complexity:** O(1)

- `remove_at_index(self, index)`
  - **Time Complexity:** O(n)
  - **Space Complexity:** O(1)

- `remove_node(self, value)`
  - **Time Complexity:** O(n)
  - **Space Complexity:** O(1)

- `size_of_linked_list(self)`
  - **Time Complexity:** O(n)
  - **Space Complexity:** O(1)

## Usage Example

Here's an example of how to use the `MyLinkedList` class:

```python
from my_linked_list import MyLinkedList

my_linked_list = MyLinkedList()

# Appending values to the linked list
my_linked_list.append(10)
my_linked_list.append(20)
my_linked_list.append(30)

# Displaying the linked list
my_linked_list.display()
