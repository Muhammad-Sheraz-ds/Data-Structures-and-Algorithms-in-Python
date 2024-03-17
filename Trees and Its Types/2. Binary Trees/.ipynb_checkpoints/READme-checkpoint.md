# Binary Tree Implementation

This Python implementation provides a basic Binary Tree structure with various functionalities using linked nodes.

## Binary Tree

A Binary Tree is a hierarchical data structure in which each node has at most two children, referred to as the left child and the right child.

<div style="display: flex;">
<img style="width: 52%; height: auto;" src="../../Images/bt3.png">
<img style="width: 47%; height: auto;" src="../../Images/bt2.png">
</div>


## Class Structure

### Node
- **Attributes:**
  - `data`: The value of the node.
  - `left`: Reference to the left child node.
  - `right`: Reference to the right child node.

### BinTree
- **Attributes:**
  - `root`: Reference to the root node.
  
### Functions and Time Complexity (Worst and Best Cases) and Space Complexity

| Function                              | Description                                   | Worst Case Time Complexity | Best Case Time Complexity | Space Complexity (Auxiliary) |
|---------------------------------------|-----------------------------------------------|----------------------------|---------------------------|-------------------------------|
| `addroot(n)`                          | Adds the root element to the BinTree.         | O(1)                       | O(1)                      | O(1)                          |
| `addleftchild(n, p)`                  | Adds the element as a left child node.        | O(n)                       | O(1)                      | O(1)                          |
| `addrightchild(n, p)`                 | Adds the element as a right child node.       | O(n)                       | O(1)                      | O(1)                          |
| `Display()`                           | Displays the nodes of the BinTree.            | O(n)                       | O(n)                      | O(h)                          |
| `level_order_travsrsal()`             | Level-order traversal of the BinTree.         | O(n)                       | O(n)                      | O(h)                          |
| `Inorder_Traversal()`                 | In-order traversal of the BinTree.            | O(n)                       | O(n)                      | O(h)                          |
| `Pre_Order_Traversal()`               | Pre-order traversal of the BinTree.           | O(n)                       | O(n)                      | O(h)                          |
| `Post_Order_Traversal()`              | Post-order traversal of the BinTree.          | O(n)                       | O(n)                      | O(h)                          |
| `remove(val)`                         | Removes a node with a given value from the BinTree. | O(n)                  | O(n)                      | O(h)                          |
| `Reverse_level_order_travsrsal()`    | Reverse level-order traversal of the BinTree.  | O(n)                       | O(n)                      | O(h)                          |
| `search(val)`                        | Searches for a node with a given value in the BinTree. | O(n)                | O(1)                      | O(1)                          |

**Note:**
- Time complexity is given in terms of the number of nodes (n) or the height of the tree (h).
- Space complexity is specified for auxiliary space, not including the space required by the input and output.

Feel free to use this Binary Tree implementation for your projects and modify it as needed!
