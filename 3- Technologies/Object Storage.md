
Object storage manages data as self-contained objects — each containing the data, metadata, and a unique identifier.  It’s designed for enormous scalability and durability across distributed systems.

---
### `Key Ideas`

- **Architecture:** Flat namespace with “buckets” or “containers” instead of folders.
    
- **Access:** Data accessed via APIs (e.g., **REST**, **S3 API**) rather than file paths.
    
- **Metadata:** Each object can store custom metadata for organization or indexing.
    
- **Performance:** Optimized for high throughput, not for low-latency random access.
    
- **Scalability:** Infinitely scalable; automatically distributes data across nodes and regions.
    
- **Durability:** Built with redundancy and replication across multiple data centers.
    
- **Examples:**
    
    - **Amazon S3 (Simple Storage Service)**
        
    - **Azure Blob Storage**
        
    - **Google Cloud Storage (GCS)**
        
    - **MinIO** (self-hosted object storage)
        
    - **Ceph Object Gateway (RADOS)**

---
### `Use Cases`

- Storing unstructured data such as images, videos, logs, and backups.
    
- Web and mobile app file uploads.
    
- Archival storage or data lakes.
    
- Content delivery and static website hosting.

---
### `Connected Notes`

- [[Storage Architecture Layers]]
- [[Bucket]]