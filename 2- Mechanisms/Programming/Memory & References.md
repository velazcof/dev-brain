
### `Definition`

**Memory & references** describe how a program stores data in memory and how program elements **locate and interact with that data**. They define the relationship between values, storage locations, and the names or references used to access them.

---
### `How It Works`

When a program runs, data is allocated into memory regions. 

Variables either store values directly or store references that point to specific memory locations where values reside.

Multiple references can point to the same memory location, allowing shared access to data.  
How memory is allocated, accessed, and reclaimed depends on the execution model and language semantics.

---
### `Why it Exists`

- To enable programs to **store and retrieve data**
- To allow **efficient sharing and manipulation** of values
- To separate **identity** (where data lives) from **representation** (how it is accessed)
- To support complex data structures and program execution

---
### `Connected Notes`

- [[Programming Fundamentals]]
- [[Stack (Memory)]]
- [[Heap (Memory)]]
- [[Pointers]]
- [[Pass by Value]]
- [[Pass by Reference]]
- [[Garbage Collection]]