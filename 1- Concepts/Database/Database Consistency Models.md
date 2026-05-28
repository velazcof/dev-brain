
**Consistency models** define the rules that determine when and how updates to data become visible to users or systems. 

They describe the guarantees a database provides about the ordering and visibility of operations, especially under concurrent access or distributed conditions.

---
### `Key Ideas`

- **Visibility Guarantees**  
    A consistency model specifies when a write becomes observable to other transactions or nodes.
    
- **Ordering Rules**  
    It defines whether operations appear to occur in a single global order or may be seen differently across clients.
    
- **Strong vs Weak Consistency**  
    Some systems guarantee that all clients see the same data immediately, while others allow temporary divergence.
    
- **Trade-Off with Availability and Latency**  
    Stronger consistency often increases coordination overhead, reducing performance or availability.
    
- **Local vs Distributed Scope**  
    In single-node systems, consistency mainly concerns transaction isolation.  
    In distributed systems, it governs replication and cross-node agreement.
    
- **Independent from Mechanism**  
    Consistency models define what guarantees are provided, not how they are implemented (e.g., via locking, consensus, replication).

---
### `Connected Notes`

- [[Database Properties]]