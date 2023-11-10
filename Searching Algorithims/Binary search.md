## Binary Search

Binary search is a divide-and-conquer approach for finding a target value in a sorted list. It continuously divides the search interval in half, narrowing down the possibilities.

### Algorithm

1. Begin with the entire sorted list.
2. Compare the target value with the middle element of the list.
3. If the target matches the middle element, return its index.
4. If the target is less than the middle element, continue the search in the lower half of the list.
5. If the target is greater than the middle element, continue the search in the upper half of the list.
6. Repeat the process until the element is found or the entire list is checked.

### Time Complexity

- **Best Case:** The element being searched is the middle element of the list. Time complexity: O(1).
- **Worst Case:** The element might be the last one or might not be present in the list at all. Time complexity: O(log n), where 'n' is the number of elements in the list.

### Space Complexity

Binary search operates with a constant amount of additional space. Therefore, its space complexity is O(1).

### General Analysis

- **Best Case Time Complexity:** O(1)
- **Worst Case Time Complexity:** O(log n)
- **Average Case Time Complexity:** O(log n)
- **Space Complexity:** O(1)

Binary search is highly efficient for searching large sorted arrays, significantly reducing the number of comparisons needed when compared to linear search. It is not suitable for unsorted lists and can only be applied to sorted collections.
