
**Buffer Management** is the mechanism that controls how database pages are loaded into memory, cached, and written back to disk. It optimizes the interaction between memory and persistent storage to improve performance.

---
### `How It Works`

- **Buffer Pool Usage**  
    Maintains an in-memory region (buffer pool) where frequently accessed pages are stored.

- **Page Loading**  
    When a requested page is not in memory, it is fetched from disk into the buffer pool.

- **Dirty Page Tracking**  
    Modified pages are marked as dirty and later written back to disk in coordination with the storage subsystem.

- **Replacement Strategy**  
    Uses page replacement algorithms to decide which pages to evict when memory is full.

- **Coordination with Other Mechanisms**  
    Works closely with query execution and storage mechanisms to minimize disk I/O.

---
### `Why It Exists`

- To reduce expensive disk reads and writes
- To improve overall query performance
- To manage limited memory efficiently
- To balance durability requirements with performance

---
### `Connected Notes`

- [[Database Engine]]
- [[Buffer Pool]]
- [[Caching Policies]]
- [[Page Replacement Algorithms]]