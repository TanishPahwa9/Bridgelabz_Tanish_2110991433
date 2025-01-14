# JavaScript Map and Set

## Topics Covered
- **Introduction to `Map` and `Set`**
- Key use cases for `Map` and `Set` in programming
- Differences between `Map`, `Set`, and other data structures (e.g., Objects, Arrays)
- How to use `Map` and `Set` effectively

---

## Introduction to `Map` and `Set`

- **`Map`**: A collection of key-value pairs where keys can be of any data type, and values can be anything. Maps preserve the insertion order of keys.
- **`Set`**: A collection of unique values, meaning no duplicates are allowed. Sets also preserve the insertion order.

| Feature            | `Map`                     | `Set`                    |
|--------------------|---------------------------|--------------------------|
| **Stores Values**  | Key-value pairs           | Unique values            |
| **Allows Duplicates?** | No                      | No                       |
| **Keys**           | Any data type             | Not applicable           |
| **Use Case**       | Caching, Lookup tables    | Storing unique values    |

---

## `Map` in JavaScript

### Creating a `Map`

You can create a new `Map` using the `Map` constructor. The map can be initialized with key-value pairs.

```javascript
let studentGrades = new Map([
  ['Alice', 'A'],
  ['Bob', 'B'],
  ['Charlie', 'C']
]);
