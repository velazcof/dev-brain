
The **S3 API** is a **RESTful protocol standard** created by **Amazon Web Services** for interacting with **object storage systems**. It defines the operations, conventions, and request/response formats for managing **buckets** and **objects** over **HTTP/HTTPS**.

Today, it serves as the **de facto industry standard** for object storage communication, implemented by many cloud and open-source providers for interoperability.

---
### `Purpose`

- Provides a **uniform and vendor-neutral interface** to store, retrieve, and manage data in object storage.
    
- Enables **cross-compatibility** among storage systems — applications built for AWS S3 can work with any S3-compatible platform.
    
- Simplifies integration for tools, SDKs, and automation frameworks by adhering to a single, widely supported API model.
    
- Bridges cloud, on-prem, and hybrid storage solutions under one access protocol.

---
### `Structure`

- **Resources:**
    
    - **Buckets:** Logical containers for storing objects.
        
    - **Objects:** Individual data units containing file content, metadata, and a unique key (path).
    
- **Operations (HTTP-based):**
    
    - `GET` → Retrieve an object or list objects in a bucket.
    - `PUT` → Upload or create an object.
    - `DELETE` → Remove an object or bucket.
    - `HEAD` → Retrieve metadata.
    - `POST` → Used for multipart uploads or form-based uploads.
    
- **Security & Authentication:**
    
    - Uses **AWS Signature Version 4** for request signing (HMAC-based).
        
    - Supports **Access Control Lists (ACLs)** and **IAM policies**.
        
    - Optional **pre-signed URLs** for temporary, scoped access.
    
- **Adoption:**  
    Widely implemented by cloud and open-source systems, including **AWS S3**, **MinIO**, **Ceph RADOS Gateway**, **Wasabi**, and **DigitalOcean Spaces**.

---
### `Connected Notes`

- [[Object Storage]]
- [[Bucket]]