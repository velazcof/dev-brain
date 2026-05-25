
### `Definition`

**Database Access Control** is the mechanism by which a database system restricts and manages who can access data and what operations they are allowed to perform. It enforces permissions at the database level to protect data integrity and security.

---
### `How It Works`

- **Authentication**  
    The system verifies the identity of a user or application before granting access.

- **Authorization**  
    Permissions determine which actions (read, write, modify, delete) are allowed on specific database objects.

- **Role-Based Access**  
    Permissions are often grouped into roles that can be assigned to users.

- **Privilege Enforcement**  
    The database engine checks permissions during query execution and blocks unauthorized operations.

- **Granularity**  
    Access may be controlled at the database, schema, table, column, or even row level depending on the system.

---
### `Why It Exists`

- Protects sensitive data from unauthorized access
- Prevents accidental or malicious modification
- Enforces separation of responsibilities
- Supports compliance and governance requirements

---
### `Connected Notes`

- [[Database Operations]]