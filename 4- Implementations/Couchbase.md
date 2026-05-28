
**Couchbase** is a distributed document-oriented database management system designed for high-performance applications requiring flexible data models and scalability. It stores data as JSON documents and supports both key-based access and SQL-like querying.

---
### `Key Capabilities`

- JSON document storage with flexible schemas
    
- Distributed architecture with automatic sharding
    
- SQL-like querying through a document query language
    
- Built-in replication and high availability
    
- Integrated caching and memory-first design

---
### `Usage Basics`

- Deploy Couchbase server or connect to a managed cluster
    
- Create a bucket (data container)
    
- Insert a document:
    `{`  
      `"name": "Franco",`  
      `"age": 23`  
    `}`
    
- Query documents:
    `SELECT * FROM bucket WHERE name = "Franco";`

---
### `Challenges`

- Distributed configuration adds operational complexity
    
- Query performance depends on index configuration
    
- Schema flexibility requires discipline in large teams
    
- Scaling and memory tuning require planning

---
### `Connected Notes`

- [[Document DBMS]]