
**Database Replication** is the process of copying and synchronizing data across multiple database instances to improve availability, reliability, and scalability. It ensures that multiple nodes maintain consistent or near-consistent copies of the same data.

---
### `Key Ideas`

- **Redundant Data Copies**  
    Data is maintained on more than one database instance to reduce single points of failure.
    
- **Primary–Replica Models**  
    Some systems designate a primary node for writes and replicas for reads.
    
- **Synchronous vs Asynchronous Replication**  
    Replication may occur immediately during a transaction or with delay, affecting consistency guarantees.
    
- **Read Scaling**  
    Replicas can serve read queries to distribute workload.
    
- **Failure Recovery**  
    If a primary node fails, a replica may be promoted to maintain availability.
    
- **Trade-Offs with Consistency**  
    Replication strategies may introduce replication lag or consistency compromises.
    
- **Distinct from Backup**  
    Replication improves availability, but does not replace backup for disaster recovery.

---
### `Connected Notes`

- [[Database Operations]]