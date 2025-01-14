# Core JavaScript Concepts: Comparisons, Conditional Branching, and User Interaction

## Overview

This branch focuses on core JavaScript concepts, emphasizing the mechanics of **Comparisons**, **Conditional Branching**, and **User Interaction** through methods like `alert`, `prompt`, and `confirm`. It provides insights into their practical use and best practices for effective coding.

---

## Topics Covered

### Comparisons

Comparisons allow evaluating values against each other using operators.

#### Types of Comparisons:

- **Loose Equality (==)**: Compares values after type coercion.
- **Strict Equality (===)**: Compares values and types.
- **Relational Operators**: (`<`, `>`, `<=`, `>=`) Compare numerical or string values lexicographically.

#### Examples:

```javascript
console.log(1 == '1'); // true (type coercion)
console.log(1 === '1'); // false (strict comparison)
console.log(10 > 5); // true
console.log('apple' > 'banana'); // false (lexicographical order)
