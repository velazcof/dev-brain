
**Extents** are contiguous groups of database pages allocated together as a unit within a data file. They are used to manage space allocation efficiently and reduce fragmentation.

---
### `How It Works`

- **Grouped Page Allocation**  
    Instead of allocating single pages individually, the system allocates a block of pages as one extent.

- **Contiguous Storage**  
    Extents are typically stored in contiguous disk regions to improve sequential I/O performance.

- **Space Management Tracking**  
    The database maintains metadata to track which extents are free, allocated, or partially used.

- **Growth Handling**  
    When additional storage is required, new extents are allocated and associated with tables or indexes.

---
### `Why It Exists`

- To improve disk I/O efficiency through contiguous storage
- To reduce fragmentation within data files
- To simplify space management and allocation tracking
- To support scalable growth of tables and indexes

---
### `Connected Notes`

- [[Storage Subsystem]]
- [[Database Pages]]