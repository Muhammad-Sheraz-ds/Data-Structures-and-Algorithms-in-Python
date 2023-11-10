## Linear Search

Linear search, also known as sequential search, is a simple method for finding a target value within a list. It checks each element in the list sequentially until the desired element is found or the end of the list is reached.

### Algorithm

1. Begin from the first element in the list.
2. Compare each element with the target value.
3. If the element matches the target, return its index.
4. If the target is not found in the entire list, return -1.

### Time Complexity

- **Best Case:** The element being searched is the first element of the list. Time complexity: O(1).
- **Worst Case:** The element might be the last one or might not be present in the list at all. Time complexity: O(n), where 'n' is the number of elements in the list.

### Space Complexity

Linear search only requires a constant amount of extra space for the loop variables or pointers. Thus, its space complexity is O(1).

### General Analysis

- **Best Case Time Complexity:** O(1)
- **Worst Case Time Complexity:** O(n)
- **Average Case Time Complexity:** O(n)
- **Space Complexity:** O(1)

Linear search is a straightforward algorithm suitable for small lists or unsorted data. However, its performance degrades significantly with large datasets, making it inefficient compared to more optimized search algorithms like binary search or hash tables.

