
**hbase shell** is the command-line interface used to interact with Apache HBase databases. It allows users to create tables, insert and retrieve data, and manage HBase structures through a terminal environment.

---
### `Key Capabilities`

- Table creation and column family management
    
- Row-level data insertion and retrieval
    
- Basic administrative operations
    
- Direct interaction with distributed HBase clusters
    
- Scriptable command execution

---
### `Usage Basics`

- Start the HBase shell:
    hbase shell
    
- Create a table:
    create 'users', 'info'
    
- Insert data:
    put 'users', 'user1', 'info:name', 'Franco'
    
- Retrieve data:
    get 'users', 'user1'

---
### `Challenges`

- Limited to HBase systems
    
- Data modeling must align with column-family design
    
- No support for relational joins
    
- Operational complexity due to distributed architecture

---
### `Connected Notes`

- [[DB-Specific CLI Clients]]