
A **bucket** is the fundamental **storage container** used in **object storage systems** (like AWS S3, Google Cloud Storage, or Firebase Storage).

It serves as a **logical namespace** where objects (files) and their metadata are stored, managed, and accessed via unique keys or URLs.

---
### `Key Ideas`

- **Container for Objects:** A bucket holds data objects — each object consists of the file’s data, its metadata, and a unique identifier (key).
    
- **Flat Structure:** Buckets do not use traditional folders; hierarchy is simulated through naming conventions (e.g., `images/cat.jpg` is just part of the object’s key).
    
- **Namespace:** Each bucket name must be globally unique (within a provider’s namespace). It defines the access endpoint for all objects it contains.
    
- **Access Control:** Permissions and policies (ACLs, IAM roles) are applied at the bucket level, controlling who can upload, download, or modify objects.
    
- **Versioning & Lifecycle:** Buckets can enable object versioning, retention policies, and automatic lifecycle management (archival or deletion).
    
- **Regionality:** Buckets are created in specific **regions** or **multi-regional zones**, determining data location and latency.
    
- **Examples:**
    
    - **AWS S3 Bucket:** `my-app-uploads` → accessed via `https://my-app-uploads.s3.amazonaws.com`
        
    - **GCP / Firebase Bucket:** `my-app.appspot.com` → used by Firebase Storage SDK
        
    - **Azure Blob Container:** Equivalent concept called a _container_ instead of bucket.

---
### `Use Cases`

- Storing and organizing files (media, logs, backups, static assets).
    
- Managing data accessibility through policies and permissions.
    
- Serving static websites or app content directly from a storage endpoint.
    
- Integrating with CDNs or serverless architectures (e.g., CloudFront + S3, Firebase Hosting + Storage).
    
- Data archival and lifecycle automation.

---
### `Connected Notes`

- [[Object Storage]]