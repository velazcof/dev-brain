
**Database Data Files** are the physical files on disk that store a database’s persistent data and structural information. They contain the organized collection of pages and extents that represent tables, indexes, and other database objects.

---
### `How It Works`

- **Persistent Storage Containers**  
    Data files act as containers for database pages allocated by the storage subsystem.

- **Logical-to-Physical Mapping**  
    Tables and indexes are mapped to pages within one or more data files.

- **Extent Allocation**  
    Storage space within data files is managed through extents that group pages together.

- **File Growth Management**  
    Data files can expand as more storage is required for database objects.

- **Coordination with Logging**  
    Works alongside log files to ensure durable and recoverable data operations.

---
### `Why It Exists`

- To provide durable, persistent storage for database contents
- To organize structured data into manageable physical containers
- To support scalable growth of database objects
- To enable recovery and durability mechanisms

---
### `Connected Notes`

- [[Storage Subsystem]]