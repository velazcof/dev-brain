
The **stack** is a memory mechanism that manages **temporary execution data** in a **last-in, first-out (LIFO)** order. It is used to store function call information such as local variables, parameters, and return addresses during program execution.

---
### `How It Works`

- When a function is called, a **stack frame** is pushed onto the stack.
- The stack frame typically contains:
    - function parameters
    - local variables
    - return address
    - saved execution state
- As functions call other functions, new frames are added on top.
- When a function returns, its stack frame is **popped**, restoring the previous execution state.
- Stack allocation and deallocation are **automatic and deterministic**, following execution flow.

---
### `Why It Exists`

- To support **function calls and returns** efficiently.
- To provide **fast allocation and cleanup** of temporary data.
- To enforce **execution isolation** between function calls.
- To enable structured control flow and recursion.
- To simplify memory management for short-lived data.

---
### `Connected Notes`

- [[Memory & References]]