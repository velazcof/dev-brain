
**Index Structures** are data structures used by a database system to improve the efficiency of data retrieval operations. They provide alternative access paths to records without requiring full scans of data files.

---
### `How It Works`

- **Auxiliary Data Organization**  
    Indexes store references to data records in a structured format separate from the main table storage.

- **Search Optimization**  
    When a query includes indexed fields, the system can use the index to locate matching records directly.

- **Structured Data Layouts**  
    Common implementations rely on tree-based or hash-based structures to support efficient lookups.

- **Maintenance on Data Changes**  
    Insert, update, and delete operations also update corresponding index entries.

- **Integration with Query Processing**  
    The query planner and optimizer evaluate whether using an index reduces execution cost.

---
### `Why It Exists`

- To reduce the need for full table scans
- To improve query performance for filtering and lookups
- To support efficient ordering and range queries
- To enable scalable performance as data grows

---
### `Connected Notes`

- [[Storage Subsystem]]