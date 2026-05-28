
**Storage Subsystem** is the mechanism responsible for organizing, persisting, and retrieving the physical representation of database data. It manages how logical data structures are mapped to files, pages, and durable storage media.

---
### `How It Works`

- **Physical Data Organization**  
    Structures data into units such as pages and extents that can be read from or written to disk.
    
- **File Management**  
    Maintains data files and log files that store persistent database state.
    
- **Index Coordination**  
    Organizes and maintains index structures to support efficient data access.
    
- **Durability Integration**  
    Coordinates logging and checkpointing to ensure changes are safely persisted.
    
- **Interaction with Buffer Management**  
    Works with in-memory buffers to minimize direct disk access.

---
### `Why It Exists`

- To provide reliable persistent storage for database data
    
- To abstract physical storage details from higher-level mechanisms
    
- To enable efficient disk I/O and data retrieval
    
- To support durability and crash recovery

---
### `Connected Notes`

- [[Database Engine]]
- [[Database Pages]]
- [[Extents]]
- [[Database Data Files]]
- [[Index Structures]]
- [[Write-Ahead Logging]]
- [[Checkpointing]]