
**Redis** is an in-memory key-value database system designed for high-performance data storage and retrieval. It is commonly used when low-latency access and high throughput are more important than complex relational querying.

---
### `Key Capabilities`

- In-memory data storage for extremely fast read/write operations
    
- Key-value access model with support for additional data structures
    
- Optional persistence mechanisms for durability
    
- Built-in replication and clustering support
    
- Suitable for caching, session storage, and real-time systems

---
### `Usage Basics`

- Start the Redis server:
    `redis-server`
    
- Connect using the CLI:
    `redis-cli`
    
- Basic operations:
    `SET user:1 "Franco"`  
    `GET user:1`  
    `DEL user:1`

---
### `Challenges`

- Primarily optimized for key-based access, not complex querying
    
- Memory usage must be carefully managed
    
- Persistence configuration requires tuning depending on durability needs
    
- Not suited for relational-style joins or structured query workloads

---
### `Connected Notes`

- [[Key-Value DBMS]]