
**Database Locking** is the mechanism that controls concurrent access to data by restricting how multiple transactions read or modify shared resources. It prevents conflicting operations from corrupting data or violating isolation guarantees.

---
### `How It Works`

- **Locks as Access Controls**  
    When a transaction accesses data, it acquires a lock that defines permitted operations (e.g., shared or exclusive).

- **Conflict Detection**  
    If another transaction requests an incompatible lock on the same resource, it must wait or be denied.

- **Lock Granularity**  
    Locks may apply at different levels, such as rows, pages, or tables.

- **Lock Lifecycle**  
    Locks are typically held for a defined duration, often until the transaction commits or rolls back.

- **Coordination with Transaction Management**  
    Lock acquisition and release are managed as part of transaction boundaries.

---
### `Why It Exists`

- To prevent inconsistent updates from concurrent transactions
- To enforce isolation behavior
- To maintain data integrity under simultaneous access

---
### `Connected Notes`

- [[Transaction Management]]