
**Amazon DynamoDB** is a fully managed key-value and document database service designed for scalable, low-latency applications. It is commonly used in cloud-native systems that require automatic scaling and high availability without managing infrastructure.

---
### `Key Capabilities`

- Managed service with automatic scaling
    
- Key-value and document data support
    
- Partition-based data distribution
    
- Built-in replication and high availability
    
- Fine-grained access control and integration with cloud identity systems

---
### `Usage Basics`

- Create a table through the cloud console or CLI
    
- Define a primary key (partition key, optionally sort key)
    
- Insert an item:
    `{`  
      `"UserId": "123",`  
      `"Name": "Franco"`  
    `}`
    
- Query by primary key using SDK or CLI

---
### `Challenges`

- Query patterns must align with key design
    
- Limited support for complex relational queries
    
- Cost management requires attention at scale
    
- Vendor lock-in considerations in cloud environments

---
### `Connected Notes`

- [[Key-Value DBMS]]