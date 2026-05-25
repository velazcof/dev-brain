
### `Definition`

**Pointers** are values that **store the memory address of another value**, allowing indirect access to data stored elsewhere in memory.

They enable programs to reference, share, and manipulate data without copying it.

---
### `How It Works`

- A pointer holds the **address** of a memory location, not the value itself.
    
- Dereferencing a pointer accesses the value stored at that address.
    
- Multiple pointers can reference the same memory location.
    
- Pointer values can be reassigned to point to different addresses.
    
- Pointer usage often interacts closely with stack and heap allocation.

---
### `Why It Exists`

- To allow **efficient data sharing** without copying large values.
    
- To enable **dynamic memory management**.
    
- To support data structures like linked lists, trees, and graphs.
    
- To allow low-level control over memory and performance.
    
- To enable interaction with hardware, system APIs, and foreign code.

---
### `Connected Notes`

- [[Memory & References]]