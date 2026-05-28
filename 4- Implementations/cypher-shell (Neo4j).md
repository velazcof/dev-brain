
**cypher-shell** is the command-line client used to interact with Neo4j graph databases. It allows users to execute Cypher queries and manage graph data directly from a terminal.

---
### `Key Capabilities`

- Interactive execution of Cypher queries
    
- Script execution for batch graph operations
    
- Direct connection to local or remote Neo4j instances
    
- Support for authentication and encrypted connections
    
- Integration into automation and deployment workflows

---
### `Usage Basics`

- Connect to a Neo4j instance:
    `cypher-shell -u username -p password`
    
- Run a query:
    `MATCH (n) RETURN n LIMIT 10;`
    
- Execute a script:
    `cypher-shell -f script.cypher`

---
### `Challenges`

- Limited to Neo4j systems
    
- Requires familiarity with Cypher syntax
    
- Less visual feedback compared to graphical clients
    
- Advanced administration may require additional tools

---
### `Connected Notes`

- [[DB-Specific CLI Clients]]