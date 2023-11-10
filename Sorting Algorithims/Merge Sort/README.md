# Merge Sort

### Algorithm
Merge Sort is a divide-and-conquer algorithm that divides an unsorted array into two halves, sorts each half, and then merges them back together.

### Algorithm Steps
1. Divide the unsorted array into two halves.
2. Recursively sort the two halves.
3. Merge the sorted halves to produce a single sorted array.

### Usage
Merge Sort is widely used for sorting linked lists and arrays efficiently.

### Advantages
- Efficient for large datasets and arrays.
- Stable sorting algorithm.
- Outperforms other sorting algorithms for larger datasets.

### Disadvantages
- Uses extra space proportional to the size of the array.
- Not suitable for small arrays or lists.
- Complex to implement for linked lists.

### Complexities
- **Time Complexity:**
  - Best Case: O(n log n)
  - Worst Case: O(n log n)
  - Average Case: O(n log n)
  - Merge operation takes O(n) time, and log n levels of recursion for dividing the array.
- **Space Complexity:**
  - O(n) - Requires additional space for the temporary array during the merging process.

This algorithm's efficiency and stability make it a popular choice for sorting large datasets, but its space complexity might limit its use in memory-restricted scenarios.
