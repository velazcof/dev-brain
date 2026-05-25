
### `Definition`

Stacks are **linear data structures** that follow the **Last-In, First-Out (LIFO)** principle, where elements are added and removed only from one end, called the **top**. They model scenarios where the most recent item must be processed first.

---
### `Key Ideas`

- Access is restricted to a single end (**top**).
    
- Supports only a limited set of operations: push, pop, peek.
    
- No direct access to arbitrary elements.
    
- Can be implemented using arrays/vectors or linked lists.
    
- Widely used to manage temporary state and execution order.

---
### `Big-O Performance`

| Operation             | Time Complexity | Notes                             |
| --------------------- | --------------- | --------------------------------- |
| **Push**              | **O(1)**        | Add element to the top            |
| **Pop**               | **O(1)**        | Remove element from the top       |
| **Peek / Top**        | **O(1)**        | Read top element without removing |
| **Search**            | **O(n)**        | Must traverse elements            |
| **Access (by index)** | **O(n)**        | No random access                  |
| **Space Complexity**  | **O(n)**        | Stores n elements                 |

---
### `Connected Notes`

- [[Data Structures]]