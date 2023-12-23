# Lecture 2: Hash Functions and Collision Handling

## Introduction

In this lecture, we explore the properties of good hash functions and various techniques for handling collisions. Understanding these concepts is crucial for designing efficient and reliable hash tables.

## Topics

### 1. Properties of Good Hash Functions

A good hash function exhibits the following properties:

1. **Deterministic:** The same input always produces the same hash value.
2. **Efficient:** Computationally efficient for quick calculations.
3. **Uniform Distribution:** Hash values are evenly distributed to minimize collisions.
4. **Avalanche Effect:** Small changes in input result in substantially different hash values.
5. **Pre-image Resistance:** Computationally infeasible to reverse the hash function.

### 2. Collision Handling

#### 2.1 Chaining

- **Insert Chaining Function:**
  - *Description:* Inserts a key-value pair using chaining to handle collisions.
  - *Time Complexity:* O(1) average case, O(n) worst case (due to potential collisions).
  - *Space Complexity:* O(n), where n is the number of elements.

- **Search Chaining Function:**
  - *Description:* Searches for a key using chaining.
  - *Time Complexity:* O(1) average case, O(n) worst case (due to potential collisions).
  - *Space Complexity:* O(1)

#### 2.2 Linear Probing

- **Insert Linear Probing Function:**
  - *Description:* Inserts a key-value pair using linear probing to handle collisions.
  - *Time Complexity:* O(1) average case, O(n) worst case (due to potential collisions).
  - *Space Complexity:* O(n), where n is the number of elements.

- **Search Linear Probing Function:**
  - *Description:* Searches for a key using linear probing.
  - *Time Complexity:* O(1) average case, O(n) worst case (due to potential collisions).
  - *Space Complexity:* O(1)

#### 2.3 Quadratic Probing

- **Insert Quadratic Probing Function:**
  - *Description:* Inserts a key-value pair using quadratic probing to handle collisions.
  - *Time Complexity:* O(1) average case, O(n) worst case (due to potential collisions).
  - *Space Complexity:* O(n), where n is the number of elements.

- **Search Quadratic Probing Function:**
  - *Description:* Searches for a key using quadratic probing.
  - *Time Complexity:* O(1) average case, O(n) worst case (due to potential collisions).
  - *Space Complexity:* O(1)

## Conclusion

Understanding the properties of good hash functions and the various collision handling techniques is crucial for designing efficient hash tables. Each collision handling method has its time and space complexity considerations, and the choice depends on the specific requirements of the application.

Feel free to use and customize this README file for your educational or project purposes.
