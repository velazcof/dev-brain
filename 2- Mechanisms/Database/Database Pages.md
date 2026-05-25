
### `Definition`

**Database Pages** are fixed-size units of storage used by a database system to read and write data between memory and disk. They serve as the fundamental I/O unit within the storage subsystem.

---
### `How It Works`

- **Fixed-Size Blocks**  
    Data files are divided into pages of a predefined size determined by the database system.

- **Row and Index Storage**  
    Pages contain rows, index entries, and metadata depending on their purpose.

- **I/O Granularity**  
    Disk operations occur at the page level rather than individual rows.

- **Memory Interaction**  
    Pages are loaded into and managed within the buffer pool for processing.

- **Structural Organization**  
    Pages may contain headers, slot arrays, and data regions to organize stored records.

---
### `Why It Exists`

- To standardize disk I/O operations
- To efficiently manage memory and storage transfers
- To organize persistent data in structured blocks
- To enable indexing and recovery mechanisms to operate consistently

---
### `Connected Notes`

- [[Storage Subsystem]]