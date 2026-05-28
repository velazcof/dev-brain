
**Neo4j** is a graph database management system designed to store and query highly connected data using the graph model. It is commonly used when relationships between entities are central to the application’s logic.

---
### `Key Capabilities`

- Native graph storage of nodes and relationships
    
- Efficient traversal of multi-hop relationships
    
- Pattern-based querying through a graph-oriented query language
    
- ACID-compliant transactional support
    
- Indexing and constraint support for performance and integrity

---
### `Usage Basics`

- Install and start the Neo4j server
    
- Connect using the browser interface or a driver
    
- Create nodes and relationships:
    `CREATE (a:Person {name: "Franco"})`  
    `CREATE (b:Person {name: "Alice"})`  
    `CREATE (a)-[:KNOWS]->(b);`
    
- Query relationships:
    `MATCH (a:Person)-[:KNOWS]->(b)`  
    `RETURN a, b;`

---
### `Challenges`

- Data modeling differs significantly from relational systems
    
- Performance depends heavily on relationship design
    
- Query tuning requires understanding of graph traversal behavior
    
- Less suited for tabular or heavily relational workloads

---
### `Connected Notes`

- [[Graph DBMS]]