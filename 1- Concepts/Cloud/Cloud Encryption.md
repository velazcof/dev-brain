
**Cloud Encryption** is the process of **encoding data stored or transmitted in cloud environments** so that it remains unreadable to unauthorized parties.

It ensures that only entities possessing the correct **cryptographic keys** can access or decrypt the information.

---
### `Key Ideas`

- **Encryption at Rest:**  
    Protects stored data in databases, block, or object storage.  
    Managed via provider tools (e.g., AWS KMS, Azure Key Vault) or client-side encryption before upload.
    
- **Encryption in Transit:**  
    Secures data as it moves between users, applications, and cloud services using **SSL/TLS** and authenticated sessions.
    
- **Encryption in Use:**  
    Protects data during computation (e.g., homomorphic encryption, trusted execution environments).
    
- **Client-side vs Server-side Encryption:**
    
    - **Client-side:** Data is encrypted before sending to the cloud — provider cannot read it.
    - **Server-side:** Cloud provider handles encryption and key management automatically.
    
- **Integration with Cloud IAM:**  
    Access to encryption keys is controlled by **Identity and Access Management (IAM)** policies and roles.

---
### `Connected Notes`

- [[Cloud Data Security]]