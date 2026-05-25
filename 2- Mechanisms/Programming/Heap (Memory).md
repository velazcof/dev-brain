
### `Definition`

The **heap** is a region of memory used for **dynamic allocation**, where data can be created, accessed, and released independently of function call order. It supports objects and values whose lifetimes are not tied to a single execution scope.

---
### `How It Works`

- Memory is **allocated on demand** at runtime.
    
- Allocated data is accessed via references or pointers.
    
- Unlike the stack, heap allocation does **not follow a strict order**.
    
- Memory may be reclaimed:
    
    - manually (explicit deallocation), or
    - automatically (via garbage collection).
    
- Allocation and access are typically slower than stack operations due to bookkeeping and safety checks.

---
### `Why It Exists`

- To support **long-lived data** that outlives function calls.
    
- To allow **flexible memory usage** when size or lifetime is unknown at compile time.
    
- To enable **shared access** to data across different parts of a program.
    
- To support object-oriented and dynamic programming models.

---
### `Connected Notes`

- [[Memory & References]]