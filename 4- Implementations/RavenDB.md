
**RavenDB** is a document-oriented database management system designed for transactional applications that require flexible data structures. It stores data as JSON-like documents and provides ACID-compliant operations with built-in indexing and querying capabilities.

---
### `Key Capabilities`

- Document-based storage with flexible schemas
    
- ACID transactions across documents
    
- Automatic indexing and query support
    
- Built-in replication and high availability features
    
- Integrated tooling for monitoring and management

---
### `Usage Basics`

- Start the **RavenDB** server and access the management interface
    
- Create a document:
    `{`  
      `"Name": "Franco",`  
      `"Age": 23`  
    `}`
    
- Query documents using its query API:
    `from Users where Name = "Franco"`

---
### `Challenges`

- Data modeling differs from relational normalization
    
- Query optimization depends on understanding indexing behavior
    
- Ecosystem is smaller compared to more mainstream document databases
    
- Operational setup may vary depending on deployment mode

---
### `Connected Notes`

- [[Document DBMS]]