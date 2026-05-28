
**sqlcmd** is the command-line client used to interact with Microsoft SQL Server databases. It allows users to execute T-SQL queries, run scripts, and perform administrative tasks directly from a terminal.

---
### `Key Capabilities`

- Execute T-SQL statements interactively
    
- Run batch scripts for automation and deployments
    
- Connect to local or remote SQL Server instances
    
- Support for variables and scripting control features
    
- Integration into CI/CD and server-side workflows

---
### `Usage Basics`

- Connect to a SQL Server instance:
    `sqlcmd -S server_name -U username -P password`
    
- Run a query:
    `SELECT * FROM Users;  
    GO`
    
- Execute a script:
    `sqlcmd -S server_name -i script.sql`

---
### `Challenges`

- Limited to SQL Server systems
    
- Uses T-SQL dialect and SQL Server-specific conventions
    
- Requires familiarity with command-line usage
    
- Advanced administrative tasks may still require GUI tools

---
### `Connected Notes`

- [[DB-Specific CLI Clients]]