# Core JavaScript Concepts: Event Loop, Event Handlers, Type Conversions, and "use strict"

## Overview

This branch focuses on core JavaScript concepts, emphasizing the mechanics of the **Event Loop**, the role of **Event Handlers**, **Type Conversions**, and the impact of the `"use strict"` directive. It provides a comprehensive understanding of these topics to enhance both foundational knowledge and practical coding skills.

---

## Topics Covered

### Event Loop

The **Event Loop** is a mechanism that handles asynchronous operations, enabling non-blocking execution in JavaScript.

#### Phases of the Event Loop:

1. **Timers Phase**:
   - Executes callbacks from `setTimeout()` and `setInterval()`.
   
2. **Pending Callbacks Phase**:
   - Handles I/O callbacks (e.g., file system operations).

3. **Idle, Prepare Phase**:
   - Used internally by the system (not typically accessed directly).

4. **Poll Phase**:
   - Processes I/O events and queues callbacks.

5. **Check Phase**:
   - Executes `setImmediate()` callbacks.

6. **Close Callbacks Phase**:
   - Handles resource cleanup (e.g., closing database connections).

#### Use Cases:
- Managing asynchronous tasks and coordinating non-blocking operations in JavaScript, ensuring that the main execution thread is not blocked.

---

### Event Handlers

**Event Handlers** are functions that respond to specific events like user interactions or system events.

#### Types of Event Handlers:
- **Click Event Handlers**: Triggered when an element is clicked.
- **Mouseover Handlers**: Respond to hovering over an element.
- **Keydown Handlers**: Triggered when a key is pressed.
- **Resize Handlers**: Execute when the window is resized.
- **Scroll Handlers**: Triggered during scrolling events.

#### Best Practices:
- Use `addEventListener()` for better flexibility and control.
- Delegate events where needed to improve performance, especially with large numbers of DOM elements.

---

### Type Conversions

**Type Conversion** refers to converting one data type to another in JavaScript, either explicitly or implicitly.

#### Types of Type Conversion:

1. **Implicit (Type Coercion)**:
   - Automatic type conversion done by JavaScript, where values are converted based on the context (e.g., adding a string to a number).
   
2. **Explicit Type Conversion**:
   - Manually converting types using functions like `Number()`, `String()`, or `Boolean()`.

#### Ways to Type Cast:
- Using constructor functions like `Number()`, `String()`, and `Boolean()`.
- Using unary operators like `+` or `!!`.
- Using `parseInt()` and `parseFloat()` for converting strings to numbers.
- Using template literals for type conversion to strings.
- Using JSON methods like `JSON.stringify()` and `JSON.parse()`.

---

### "use strict"

`"use strict"` enforces stricter parsing and error handling in JavaScript code.

#### Benefits of Using `"use strict"`:
- Improves debugging by catching more errors during code execution.
- Prevents the use of undeclared variables (i.e., prevents global variable leakage).
- Enforces modern JavaScript practices for cleaner and safer code.

#### Usage:
- To enable strict mode, place `"use strict"` at the top of a script or function.

```javascript
"use strict";
// Your code here
