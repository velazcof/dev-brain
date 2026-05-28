
**Storage Area Network (SAN)** is a **high-performance storage technology** that provides **block-level storage** over a **dedicated network**, allowing servers to access remote storage as if it were locally attached disks.

---
### `Key Ideas`

- **Block-Level Storage**  
    SAN exposes raw storage blocks to servers, which then format and manage their own file systems.
    
- **Dedicated Storage Network**  
    Uses a separate, specialized network (not general LAN) to achieve:
    
    - Low latency
    - High throughput
    - Predictable performance
    
- **Specialized Protocols**
    
    - **Fibre Channel (FC)**
    - **iSCSI**
    - **FCoE**  
        Designed for reliable, high-speed data transfer.
    
- **Centralized but High-Performance**  
    Storage is centralized while maintaining performance comparable to local disks.
    
- **Enterprise-Oriented Design**  
    Common in environments requiring:
    
    - High availability
    - Redundancy
    - Strong consistency guarantees

---
### `Use Cases`

- Enterprise databases and transactional systems
    
- Virtual machine storage (e.g., VMware, Hyper-V)
    
- Mission-critical applications requiring low latency
    
- Data centers with high I/O performance requirements
    
- Environments needing centralized storage with strong reliability

---
### `Connected Notes`

- [[Storage Variants]]