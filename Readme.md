# JavaScript Concepts: Arrays, Objects, Functions, and Scope

## Topics Covered on 16 December 2024

### 1. Arrays
#### What is an Array?
An array is a data structure used to store multiple values in a single variable. Arrays are zero-indexed and can contain elements of any data type.

#### Creating and Accessing Arrays
```javascript
// Creating an array
const fruits = ['apple', 'banana', 'cherry'];

// Accessing elements
console.log(fruits[0]); // Output: 'apple'
```

#### Common Operations on Arrays
- Adding elements: `push()`, `unshift()`
- Removing elements: `pop()`, `shift()`
- Finding elements: `indexOf()`, `includes()`

#### Methods for Array Manipulation
- Iterating: `forEach()`, `map()`
- Filtering: `filter()`
- Reducing: `reduce()`
- Sorting: `sort()`

### 2. Objects
#### Introduction to Objects
Objects are collections of key-value pairs used to store structured data and represent real-world entities.

#### Creating Objects and Key-Value Pairs
```javascript
const person = {
  name: 'John',
  age: 30
};
```

#### Accessing and Modifying Object Properties
- Dot notation: `person.name`
- Bracket notation: `person['name']`
- Adding/modifying: `person.job = 'Developer';`

#### Nested Objects
Objects can contain other objects as properties:
```javascript
const user = {
  name: 'Alice',
  address: {
    city: 'New York',
    zip: 10001
  }
};
console.log(user.address.city); // Output: 'New York'
```

### 3. Normal Functions
#### Function Declarations and Expressions
- Declaration:
  ```javascript
  function greet(name) {
    return `Hello, ${name}!`;
  }
  ```
- Expression:
  ```javascript
  const greet = function(name) {
    return `Hello, ${name}!`;
  };
  ```

#### Passing Arguments and Returning Values
```javascript
function add(a, b) {
  return a + b;
}
console.log(add(2, 3)); // Output: 5
```

#### Scope Within Functions
Variables declared within a function are only accessible inside that function.

### 4. Arrow Functions
#### Syntax and Differences from Normal Functions
- Shorter syntax:
  ```javascript
  const add = (a, b) => a + b;
  ```
- No `this` binding.

#### Use Cases for Arrow Functions
Ideal for simple one-liners and callbacks.

#### Arrow Functions and `this` Context
Arrow functions do not have their own `this` context and inherit it from their surrounding scope.

### 5. Scope
#### Types of Scope
- **Global scope**: Variables declared outside of any function.
- **Function scope**: Variables declared inside a function.
- **Block scope**: Variables declared with `let` or `const` within a block.

#### Scope Chains and Variable Accessibility
Inner scopes can access variables from outer scopes but not vice versa.

#### Shadowing and Hoisting
- **Shadowing**: Variables in an inner scope can overwrite variables from an outer scope.
- **Hoisting**: Variable declarations are moved to the top of their scope during compilation.

---



