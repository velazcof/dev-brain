
**Encryption** is a **data protection technology** that converts readable information (_plaintext_) into an unreadable format (_ciphertext_) using mathematical algorithms and secret keys.

Only entities with the correct **decryption key** can restore the data to its original form.

---
### `Key Ideas`

- **Purpose:**  
    Protects data confidentiality across all stages — **in transit**, **at rest**, and **in use** — ensuring that even if data is intercepted or stolen, it remains unreadable.
    
- **Core Components:**
    
    - **Encryption Algorithm:** Defines how data is scrambled (e.g., AES, RSA, ChaCha20).
        
    - **Keys:** Unique cryptographic values used for encryption and decryption.
        
    - **Ciphers:** Implementations of encryption logic applied to data.
    
- **Types of Encryption:**
    
    - **Symmetric Encryption:** Same key for encryption and decryption — faster, used for bulk data.
        
    - **Asymmetric Encryption:** Uses a public and private key pair — used for secure communication and authentication.
    
- **Integration Points:**  
    Used in file systems, databases, network communications, email systems, and cloud storage.
    
- **Key Management:**  
    Encryption is only as strong as its key management — often handled through dedicated tools like **Key Management Services (KMS)**.

---
### `Use Cases`

- Securing communications (HTTPS, VPN, email).
    
- Protecting stored data (database, object storage, backups).
    
- Safeguarding credentials and authentication tokens.
    
- Ensuring compliance with privacy regulations (GDPR, HIPAA, ISO 27001).

---
### `Connected Notes`

- [[Data Security]]