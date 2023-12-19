### Insertion Sort

**Algorithm:**
Insertion Sort is a simple sorting algorithm that iterates through an array, growing a sorted array behind it. It repeatedly takes the next element and places it in its correct position within the sorted array. This process continues until the entire array is sorted.

**Usage:**
- Commonly used for small datasets and when the array is almost sorted.
- Often utilized in educational contexts due to its simplicity.

**Advantages:**
- Simple and easy to implement.
- Efficient for small datasets.
- Performs well for nearly sorted arrays.

**Disadvantages:**
- Less efficient on large datasets or inverse-sorted arrays.
- Time complexity increases exponentially with larger datasets.

**Complexities:**
- **Time Complexity:**
  - **Best Case:** O(n) (when the array is already sorted)
  - **Worst Case:** O(n^2) (when the array is sorted in reverse order)
  - **Average Case:** O(n^2)
- **Space Complexity:** O(1) - In-place sorting

Insertion Sort is a straightforward and effective algorithm for small datasets or mostly sorted arrays. Its simplicity in implementation and minimal space requirements make it a favorable choice in specific scenarios.
