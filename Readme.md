# JavaScript Rest Parameters, Spread Syntax, Variable Scope, and Closures

## Overview

This branch focuses on JavaScript concepts, emphasizing the mechanics of **Rest Parameters** and **Spread Syntax**, **Variable Scope**, and **Closures**. It provides a comprehensive understanding of these topics to enhance both foundational knowledge and practical coding skills.

---

## Topics Covered

### Rest Parameters and Spread Syntax

**Rest Parameters** and **Spread Syntax** are modern JavaScript features that provide flexibility in handling function arguments and array or object manipulation.

#### Rest Parameters:
Rest parameters allow functions to accept an indefinite number of arguments as an array.

#### Syntax:

```javascript
function sum(...numbers) {
  return numbers.reduce((total, num) => total + num, 0);
}
console.log(sum(1, 2, 3, 4)); // Output: 10
```
### Use Cases

- Aggregating function arguments.
- Creating functions with variable arity.

``` const arr1 = [1, 2, 3];
const arr2 = [...arr1, 4, 5];
console.log(arr2); // Output: [1, 2, 3, 4, 5]
```
### Spread Syntax

#### Syntax
```
const obj1 = { a: 1, b: 2 };
const obj2 = { ...obj1, c: 3 };
console.log(obj2); // Output: { a: 1, b: 2, c: 3 }
```

### Use Cases
- Copying and merging arrays or objects.
- Passing arrays as arguments to functions.
