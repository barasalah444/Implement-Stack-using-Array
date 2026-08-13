# Implement-Stack-using-Array

# Array-Based Stack Implementation 

A fixed-capacity Stack data structure implemented in JavaScript using a static array and top pointer.

## Features

- **push(x)**: Pushes an element onto the stack. Handles Stack Overflow if full.
- **pop()**: Removes and returns the top element. Handles Stack Underflow if empty.
- **peek()**: Returns the top element without removing it.
- **isEmpty()**: Checks if the stack is empty.
- **print()**: Prints all elements currently in the stack from top to bottom.

## Complexity Analysis

| Operation | Time Complexity | Space Complexity |
| :--- | :---: | :---: |
| push | O(1) | O(1) |
| pop | O(1) | O(1) |
| peek | O(1) | O(1) |
| isEmpty | O(1) | O(1) |

- **Overall Auxiliary Space**: O(MAX) where MAX is the fixed size (1000).

