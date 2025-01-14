# Recursion and Stack in Program Execution

## Overview

This branch focuses on fundamental programming concepts, emphasizing **Recursion** and the role of the **Stack** in managing function calls. It provides a comprehensive understanding of these topics to build foundational problem-solving skills and a deeper understanding of program execution.

---

## Topics Covered

### Recursion

Recursion is a programming technique where a function calls itself to solve a problem by breaking it into smaller sub-problems.

#### Structure:
A recursive function includes:
- **Base Case**: The condition to terminate recursion.
- **Recursive Case**: The function calls itself with a simpler version of the problem.

#### Key Characteristics:
- Simplifies problems that have repetitive, self-similar structures (e.g., tree traversal, factorial computation).
- Requires careful design to avoid infinite recursion by ensuring the base case is reached.

#### Examples:

1. **Factorial**: (n! = n × (n-1)!)

```javascript
function factorial(n) {
  if (n === 0) return 1; // Base case
  return n * factorial(n - 1); // Recursive case
}
console.log(factorial(5)); // Output: 120
