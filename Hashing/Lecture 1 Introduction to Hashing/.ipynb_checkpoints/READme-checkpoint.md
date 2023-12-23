# Lecture 1: Introduction to Hashing

**Topics:**
- What is Hashing?
- Purpose of Hashing.
- Basic Terminology (Hash Function, Hash Table, Collision).

**Explanation:**

### What is Hashing?

Hashing is a process of converting input data (or 'keys') into a fixed-size string of characters, which is typically a hash code or hash value. The goal of hashing is to efficiently index and retrieve data in a hash table. It is widely used in computer science and cryptography.

**Key Concepts:**
- **Hash Function:** A function that takes an input (or 'key') and produces a fixed-size string of characters, which is the hash value.
- **Hash Code:** The output of a hash function, representing the unique value associated with the input.

### Purpose of Hashing

The primary purposes of hashing are:

1. **Data Retrieval:** Hashing allows for efficient data retrieval by mapping keys to fixed-size hash codes, enabling quick access to corresponding values.
2. **Data Integrity:** Hash functions help ensure the integrity of data. Even a small change in the input will result in a substantially different hash code.
3. **Security:** Hashing is fundamental in cryptographic applications for creating digital signatures, password storage, and ensuring data integrity.

### Basic Terminology

#### Hash Function

A hash function takes an input (or 'key') and produces a fixed-size string of characters, the hash code. The function should be deterministic, meaning the same input will always produce the same output, and it should efficiently compute the hash value.

#### Hash Table

A hash table is a data structure that uses a hash function to map keys to hash codes and stores values associated with those keys. It allows for efficient data retrieval.

#### Collision

Collision occurs when two different keys produce the same hash code. Handling collisions is a crucial aspect of designing effective hash functions and hash tables.

**Common Collision Resolution Techniques:**
- **Chaining:** Each slot in the hash table holds a linked list of elements that hash to the same code.
- **Open Addressing:** The algorithm searches for the next available slot in the hash table when a collision occurs.


In summary, hashing is a powerful concept in computer science, providing a mechanism for efficient data retrieval, ensuring data integrity, and playing a crucial role in various applications, including security and cryptography. Understanding the basics of hash functions, hash tables, and collision resolution is fundamental to mastering the concept of hashing.

