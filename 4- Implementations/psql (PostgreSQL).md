
**psql** is the command-line client used to interact with PostgreSQL databases. It allows users to execute SQL queries, manage database objects, and run administrative commands directly from a terminal.

---
### `Key Capabilities`

- Interactive SQL query execution
    
- Script execution from files
    
- Database and role management commands
    
- Access to PostgreSQL-specific meta-commands
    
- Integration into automation and deployment workflows

---
### `Usage Basics`

- Connect to a database:
    `psql -U username -d database_name`
    
- List tables:
    `\dt`
    
- Execute a query:
    `SELECT * FROM users;`
    
- Run a script:
    `psql -d database_name -f script.sql`

---
### `Challenges`

- Limited to PostgreSQL systems
    
- Meta-commands are PostgreSQL-specific
    
- Requires familiarity with terminal workflows
    
- Advanced tuning requires deeper PostgreSQL knowledge

---
### `Connected Notes`

- [[DB-Specific CLI Clients]]