
Cloud-native storage refers to storage systems designed specifically for **containerized and microservice-based environments**.  

Instead of manually attaching volumes or configuring shared drives, cloud-native storage integrates directly with **container orchestration platforms** like Kubernetes through standardized interfaces such as the **Container Storage Interface (CSI)**.

---
### `Key Ideas`

- **Purpose:** Provides dynamic, persistent storage for containers that can move between nodes while keeping data accessible.
    
- **Integration:** Uses the **Container Storage Interface (CSI)** to connect Kubernetes pods with underlying storage (block, file, or object).
    
- **Dynamic Provisioning:** Automatically creates, mounts, and deletes volumes as pods are scheduled and removed.
    
- **Persistence:** Enables **Persistent Volumes (PV)** and **Persistent Volume Claims (PVC)** — allowing containers to retain data beyond their lifecycle.
    
- **Abstraction:** Can use cloud-managed or on-prem storage backends transparently (e.g., AWS EBS, Ceph, NFS, vSAN).
    
- **Resilience:** Often supports replication, snapshots, and scaling to maintain availability in distributed environments.
    
- **Examples:**
    
    - **Longhorn (by Rancher)** – lightweight, distributed block storage for Kubernetes.
        
    - **OpenEBS** – open-source, cloud-native block storage engine.
        
    - **Portworx**, **StorageOS**, **Rook (Ceph)** – enterprise-grade container storage platforms.
        
    - **Managed CSI Drivers:** AWS EBS CSI, Azure Disk/File CSI, GCP Persistent Disk CSI.

---
### `Use Cases`

- Providing persistent storage for **stateful containers** (e.g., databases, message queues).
    
- Managing dynamic storage provisioning in **Kubernetes clusters**.
    
- Enabling **high-availability storage** that scales with container workloads.
    
- Abstracting different backend types (block, file, object) through one interface.
    
- Supporting hybrid or multi-cloud architectures.

---
### `Connected Notes`

- [[Storage Variants]]
- [[Cloud Storage]]