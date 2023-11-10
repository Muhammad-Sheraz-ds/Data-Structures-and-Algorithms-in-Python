# Stacks Implementation

This Python implementation provides a stack structure using a linked list.

## Stacks

A stack is a fundamental data structure that follows the Last In, First Out (LIFO) principle. In a stack, elements are added and removed from the same end, typically referred to as the "top" of the stack. Stacks are widely used in computer science and have applications in various areas.

### Applications:

1. **Function Call Management:**
   - Stacks are used to manage function calls and local variables in programming languages.

2. **Expression Evaluation:**
   - Stacks play a crucial role in evaluating expressions, particularly infix to postfix conversion and postfix expression evaluation.

3. **Undo Mechanism in Software:**
   - Stacks are employed to implement undo mechanisms in applications where users can revert to previous states.

4. **Backtracking Algorithms:**
   - In algorithms like Depth-First Search (DFS), stacks are utilized to keep track of the visited nodes.

5. **Memory Management:**
   - The call stack is used for managing memory allocation and deallocation in programs.

6. **Syntax Parsing:**
   - Stacks are involved in syntax parsing and checking for balanced parentheses in mathematical expressions.

## Class Structure

### `Stacks`

- **Attributes:**
  - `top`: Reference to the top node of the stack.
  - `size`: Number of elements currently in the stack.

- **Methods:**
  - `push(value)`: Adds an element to the top of the stack.
  - `pop()`: Removes and returns the element from the top of the stack.
  - `is_empty()`: Checks if the stack is empty.
  - `peek()`: Returns the element at the top of the stack without removing it.
  - `size()`: Returns the number of elements in the stack.
  - `__str__()`: Returns a string representation of the stack.

### Functions and Time Complexity (Worst Case) and Space Complexity

| Function          | Description                               | Time Complexity (Worst Case) | Space Complexity (Auxiliary) |
|-------------------|-------------------------------------------|-----------------------------|-------------------------------|
| `push(value)`     | Adds an element to the top of the stack.   | O(1)                        | O(1)                          |
| `pop()`           | Removes and returns the top element.       | O(1)                        | O(1)                          |
| `is_empty()`      | Checks if the stack is empty.              | O(1)                        | O(1)                          |
| `peek()`          | Returns the top element without removal.  | O(1)                        | O(1)                          |
| `size()`          | Returns the number of elements in the stack.| O(1)                       | O(1)                          |
| `__str__()`       | Returns a string representation of the stack.| O(N)                      | O(N)                          |

**Note:**
- Time complexity is given in terms of the number of elements in the stack.
- Space complexity is specified for auxiliary space, not including the space required by the input and output.

Feel free to use this modified Stack implementation for your projects and modify it as needed!
