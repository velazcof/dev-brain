
**Distributed File Systems (DFS)** are **storage technologies** that store and manage files across **multiple networked machines**, while presenting them to users and applications as a **single unified file system**.

They are designed to provide **scalability, fault tolerance, and high availability** beyond what a single machine can offer.

---
### `Key Ideas`

- **Data Distributed Across Nodes**  
    Files are split, replicated, or striped across multiple servers to improve:
    
    - Capacity
    - Performance
    - Fault tolerance
    
- **Single Logical Namespace**  
    Users and applications see a single file system, even though data is physically spread across many machines.
    
- **Fault Tolerance & Replication**  
    Data is often replicated across nodes so that hardware failures do not result in data loss or downtime.
    
- **Designed for Scale-Out Systems**  
    Capacity and throughput scale horizontally by adding more nodes to the cluster.
    
- **Consistency Models Vary**  
    Different systems prioritize different trade-offs:
    
    - Strong consistency
    - Eventual consistency
    - Performance vs availability
    
- **Core Building Block of Distributed Systems**  
    Frequently used as the storage layer for:
    
    - Big data platforms
    - Cloud infrastructure
    - Container and VM environments

---
### `Use Cases`

- Large-scale data storage across clusters
    
- Big data processing platforms (e.g. analytics, ML workloads)
    
- Cloud and on-premise distributed systems
    
- High-availability file storage for multiple clients
    
- Replacing or extending traditional NAS at scale

---
### `Connected Notes`

- [[Storage Variants]]