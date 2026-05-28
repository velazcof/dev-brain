
**cqlsh** is the command-line client used to interact with Apache Cassandra databases. It allows users to execute Cassandra Query Language (CQL) statements and manage keyspaces and tables from a terminal.

---
### `Key Capabilities`

- Interactive execution of CQL queries
    
- Keyspace and table management
    
- Data insertion, update, and retrieval operations
    
- Script execution for batch tasks
    
- Direct connection to Cassandra cluster nodes

---
### `Usage Basics`

- Connect to a Cassandra node:
    `cqlsh`
    
- Create a keyspace:
    `CREATE KEYSPACE mykeyspace  
    `WITH replication = {'class': 'SimpleStrategy', 'replication_factor': 1};`
    
- Use a keyspace:
    `USE mykeyspace;`
    
- Query data:
    `SELECT * FROM users;`

---
### `Challenges`

- Limited to Cassandra systems
    
- Requires understanding of Cassandra data modeling
    
- No support for relational joins
    
- Cluster configuration and consistency tuning require deeper knowledge

---
### `Connected Notes`

- [[DB-Specific CLI Clients]]