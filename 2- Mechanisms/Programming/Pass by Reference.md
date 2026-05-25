
### `Definition`

**Pass by reference** is a parameter-passing behavior where a function receives **access to the original value**, rather than a copy, allowing the function to modify the caller’s data directly.

---
### `How It Works`

- When a function is called, a **reference (or pointer)** to the original value is passed as the parameter.
    
- The parameter and the original argument **refer to the same memory location**.
    
- Any modification made through the parameter **affects the original value**.
    
- The reference itself is often stored in the function’s stack frame.
    
- Some languages expose this explicitly, while others simulate it through references or objects.

---
### `Why It Exists`

- To allow **in-place modification** of data.
    
- To avoid **expensive copying** of large values.
    
- To enable **shared state** across function boundaries.
    
- To support performance-sensitive and low-level programming.
    
- To allow functions to return multiple results indirectly.

---
### `Connected Notes`

- [[Memory & References]]