
### `Definition`

Arrays are fixed-size, contiguous-memory data structures that store elements of the same type. They allow fast, constant-time access through indexing but cannot grow or shrink dynamically.

---
### `Key Ideas`

- Contiguous memory layout enables fast indexing.
    
- Size is fixed at creation.
    
- Insertion and deletion often require shifting elements.
    
- Ideal when the number of elements is known in advance.

---
### `Big-O Performance`

| Operation                           | Time Complexity | Notes                                           |
| ----------------------------------- | --------------- | ----------------------------------------------- |
| **Access (at index)**               | **O(1)**        | Direct memory offset                            |
| **Update (at index)**               | **O(1)**        | Same as access                                  |
| **Insert at end (if space exists)** | **O(1)**        | Only possible if preallocated                   |
| **Insert (at random index)**        | **O(n)**        | Shifts required                                 |
| **Delete (at random index)**        | **O(n)**        | Shifts required                                 |
| **Search (unsorted)**               | **O(n)**        | Linear scan                                     |
| **Search (sorted + binary search)** | **O(log n)**    | If sorted                                       |
| **Space Complexity**                | **O(n)**        | Fixed size; must allocate full capacity upfront |

---
### `Connected Notes`

- [[Data Structures]]