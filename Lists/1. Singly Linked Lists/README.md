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

# Initialize a new linked list
my_linked_list = MyLinkedList()

# Append values to the linked list
my_linked_list.append(10)
my_linked_list.append(20)
my_linked_list.append(30)

# Display the linked list
print("Linked List after appending values:")
my_linked_list.display()

# Insert a value at the beginning
my_linked_list.insert_at_beginning(5)
print("\nLinked List after inserting 5 at the beginning:")
my_linked_list.display()

# Insert a value at a specific index (e.g., index 2)
my_linked_list.insert_at_index(15, 2)
print("\nLinked List after inserting 15 at index 2:")
my_linked_list.display()

# Insert a value at the end
my_linked_list.insert_at_end(40)
print("\nLinked List after inserting 40 at the end:")
my_linked_list.display()

# Update a node at a specific index (e.g., update value at index 1 to 25)
my_linked_list.update_node(25, 1)
print("\nLinked List after updating value at index 1 to 25:")
my_linked_list.display()

# Remove the first node
my_linked_list.remove_first_node()
print("\nLinked List after removing the first node:")
my_linked_list.display()

# Remove the last node
my_linked_list.remove_last_node()
print("\nLinked List after removing the last node:")
my_linked_list.display()

# Remove a node at a specific index (e.g., index 2)
my_linked_list.remove_at_index(2)
print("\nLinked List after removing the node at index 2:")
my_linked_list.display()

# Remove a node with a specific value (e.g., remove value 15)
my_linked_list.remove_node(15)
print("\nLinked List after removing a node with value 15:")
my_linked_list.display()

# Get the size of the linked list
size = my_linked_list.size_of_linked_list()
print(f"\nSize of the linked list: {size}")
