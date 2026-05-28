
**Apache Cassandra** is a distributed wide-column database management system designed for high availability and horizontal scalability. It is commonly used in systems that require high write throughput and fault tolerance across multiple nodes.

---
### `Key Capabilities`

- Wide-column data organization with partition-based distribution
    
- Horizontal scalability across clusters
    
- High write performance and tunable consistency levels
    
- Built-in replication for fault tolerance
    
- Querying through Cassandra Query Language (CQL)

---
### `Usage Basics`

- Start a Cassandra node or connect to a cluster
    
- Create a keyspace:
    `CREATE KEYSPACE mykeyspace`  
    `WITH replication = {'class': 'SimpleStrategy', 'replication_factor': 1};`
    
- Create a table:
    `CREATE TABLE users (`  
        `id UUID PRIMARY KEY,`  
        `name text`  
    `);`
    
- Insert data:
    `INSERT INTO users (id, name) VALUES (uuid(), 'Franco');`

---
### `Challenges`

- Data modeling must align strictly with query patterns
    
- No support for traditional relational joins
    
- Operational management of clusters adds complexity
    
- Performance tuning requires understanding of partition keys and consistency settings

---
### `Connected Notes`

- [[Wide-Column DBMS]]