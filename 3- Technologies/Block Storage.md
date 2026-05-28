
Block storage splits data into uniform-sized blocks and stores them separately.  Each block is given a unique address, and the operating system or file system reassembles them into complete files.

---
### `Key Ideas`

- **Architecture:** Stores data in raw fixed-size blocks. The OS manages how blocks form files.
    
- **Flexibility:** Can be partitioned, formatted, or used directly as virtual disks.
    
- **Performance:** Offers low latency and high IOPS — perfect for databases or VMs.
    
- **Scalability:** Capacity can grow by attaching or expanding volumes.
    
- **Connectivity:** Accessed via **iSCSI**, **Fibre Channel**, or **NVMe-oF**.
    
- **Examples:**
    
    - **AWS EBS (Elastic Block Store)**
        
    - **Azure Managed Disks**
        
    - **Google Persistent Disks**
        
    - **Local SSDs** attached to compute nodes
        
    - Enterprise **SAN (Storage Area Network)** setups

---
### `Use Cases`

- Relational and NoSQL databases.
    
- Virtual machine disks and boot volumes.
    
- High-performance applications requiring consistent low latency.
    
- Transactional systems or ERP software.

---
### `Connected Notes`

- [[Storage Architecture Layers]]