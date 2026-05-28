
**MongoDB** is a document-oriented database management system that stores data in flexible, JSON-like documents. It is commonly used for applications requiring dynamic schemas and scalable distributed storage.

---
### `Key Capabilities`

- Document-based storage with nested structures
    
- Flexible schema allowing varying document formats
    
- Horizontal scaling through partitioning mechanisms
    
- Built-in indexing and aggregation capabilities
    
- Replication support for high availability

---
### `Usage Basics`

- Start the MongoDB server and connect using the shell
    
- Insert a document:
    `db.users.insertOne({ name: "Franco", age: 23 })`
    
- Query documents:
    `db.users.find({ name: "Franco" })`
    
- Create an index:
    `db.users.createIndex({ name: 1 })`

---
### `Challenges`

- Data modeling differs significantly from relational normalization
    
- Query performance depends on proper indexing
    
- Complex aggregations require understanding of pipeline stages
    
- Schema flexibility can lead to inconsistency if not disciplined

---
### `Connected Notes`

- [[Document DBMS]]