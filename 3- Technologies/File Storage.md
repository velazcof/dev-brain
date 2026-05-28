
File storage organizes data in a hierarchical structure of files and folders, much like a local file system. In the cloud, it’s typically hosted on network-attached systems that multiple compute nodes can connect to over a shared network.

---
### `Key Ideas`

- **Architecture:** Data stored as files within directories. Each file has a path and metadata (owner, permissions, timestamps).
	
- **Connectivity:** Accessed by compute nodes **over Ethernet or TCP/IP networks** using standard file-sharing protocols like **NFS (Linux/Unix)** or **SMB/CIFS (Windows)**.
    
- **Performance:** Optimized for sequential read/write and file sharing workloads.
    
- **Scalability:** Good for small–medium environments, but hierarchy limits performance at very large scale.
    
- **Management:** Easy to navigate and manage — human-readable paths and familiar structure.
    
- **Examples:**
    
    - **AWS EFS (Elastic File System)**
        
    - **Azure Files**
        
    - **Google Filestore**
        
    - Traditional **NAS (Network Attached Storage)** setups

---
### `Use Cases`

- Shared folders for internal teams or departments.
    
- Web server directories (e.g., serving static assets).
    
- Developer home directories or project shares.
    
- Applications requiring a POSIX-compliant file system.

---
### `Connected Notes`

- [[Storage Architecture Layers]]