# Lecture 3: Hashing for Strings

## Introduction

In this lecture, we delve into the specific application of hashing for strings. Hashing strings involves converting variable-length input strings into fixed-size hash codes, enabling efficient storage and retrieval. We'll explore the concept of rolling hash and discuss various applications of string hashing.

## Topics

### 1. Hashing Strings

- **Definition:** Hashing strings involves transforming variable-length input strings into fixed-size hash codes.

### 2. Rolling Hash

- **Concept:** Rolling hash is a technique that efficiently updates the hash code when a character is added or removed from the string, making it suitable for continuous hashing of sliding windows.

### 3. Applications of String Hashing

- **Substring Matching:** String hashing is commonly used in substring matching algorithms for quick comparisons of substrings.
- **Plagiarism Detection:** Hashing is employed to detect similar patterns or identical strings in large datasets for plagiarism detection.
- **Data Deduplication:** String hashing is useful in identifying and eliminating duplicate data by comparing hash codes.

## Code Explanation

### `RollingHash` Class

The `RollingHash` class implements a rolling hash with the following methods:

- `__init__(self, base, mod)`: Initializes the rolling hash.
- `append(self, char)`: Appends a character, updating the hash.
- `skip(self, char)`: Skips a character, updating the hash.
- `get_hash(self)`: Returns the current hash value.

### `hash_string` Function

The `hash_string` function hashes an entire string using the rolling hash technique.

- Parameters:
  - `input_str`: The input string to be hashed.
  - `base` (optional): The base value for the rolling hash (default is 256).
  - `mod` (optional): The modulo value for the rolling hash (default is 10^9 + 7).
- Returns:
  - The hash value of the input string.

### `substring_matching` Function

The `substring_matching` function checks if a pattern is a substring of the given text using rolling hash.

- Parameters:
  - `text`: The complete text.
  - `pattern`: The pattern to be searched in the text.
- Returns:
  - `True` if the pattern is a substring of the text, `False` otherwise.

### `plagiarism_detection` Function

The `plagiarism_detection` function detects plagiarism among a collection of documents using string hashing.

- Parameters:
  - `documents`: A list of documents.
- Returns:
  - A list of tuples representing pairs of documents with similar content.

## Test Cases

Three test functions ensure the correctness of the implemented code:

- `test_rolling_hash()`: Tests the `RollingHash` class.
- `test_substring_matching()`: Tests the `substring_matching` function.
- `test_plagiarism_detection()`: Tests the `plagiarism_detection` function.

Feel free to explore and modify the code for educational or project purposes.

## Conclusion

Understanding how to hash strings and utilize techniques like rolling hash opens up a range of applications in string manipulation, substring matching, and data processing. The ability to efficiently hash and compare strings is a valuable skill in various computational tasks.

Feel free to explore practical implementations and exercises to deepen your understanding of hashing for strings.
