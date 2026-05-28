
**PostgreSQL** is an open-source relational database management system used for storing and querying structured data with strong transactional reliability. Use it when you want a dependable SQL database for backend applications, reporting, or general-purpose data storage.

---
### `Key Capabilities`

- Strong SQL support and rich query features
    
- ACID transactions and strong concurrency handling
    
- Powerful indexing options and query optimization
    
- Extensibility (custom types, functions, extensions)
    
- Works well for both transactional workloads and moderately heavy analytics

---
### `Usage Basics`

- Start/connect (typical workflow): run the server, then connect with `psql`
    
- Common commands:
    
    - Create database: `createdb mydb`
    - Connect: `psql -d mydb`
    - Run a script: `psql -d mydb -f script.sql`

---
### `Challenges`

- Performance tuning can get deep (indexes, vacuuming, memory settings)
    
- Schema and migration discipline matters as projects grow
    
- Replication/HA setups add operational complexity compared to managed offerings

---
### `Connected Notes`

- [[Relational DBMS]]