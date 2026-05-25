### `Definition`

Vectors are **dynamic arrays**: contiguous-memory data structures that automatically resize as elements are added or removed. They provide fast indexed access while offering flexibility over fixed-size arrays.

---
### `Key Ideas`

- Store elements in contiguous memory like arrays.
    
- Automatically expand when capacity is exceeded.
    
- Allow fast random access (O(1)).
    
- Incur occasional resizing cost when growing.

---
### `Big-O Performance`

| Operation                           | Time Complexity    | Notes                                     |
| ----------------------------------- | ------------------ | ----------------------------------------- |
| **Access (at index)**               | **O(1)**           | Direct indexing via contiguous memory     |
| **Update (at index)**               | **O(1)**           | Same as access                            |
| **Append**                          | **Amortized O(1)** | Occasional resizing makes worst-case O(n) |
| **Insert (at random index)**        | **O(n)**           | Elements must shift                       |
| **Delete (at random index)**        | **O(n)**           | Elements must shift                       |
| **Search (unsorted)**               | **O(n)**           | Linear scan                               |
| **Search (sorted + binary search)** | **O(log n)**       | If the vector is sorted                   |
| **Resize / reallocate**             | **O(n)**           | Copying elements to new memory block      |
| **Space Complexity**                | **O(n)**           | Stores `n` contiguous items               |

---
### `Connected Notes`

- [[Data Structures]]