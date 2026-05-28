
**redis-cli** is the command-line client used to interact with Redis databases. It allows users to execute Redis commands, inspect keys, and perform administrative tasks directly from a terminal.

---
### `Key Capabilities`

- Interactive execution of Redis commands
    
- Direct manipulation of Redis data structures (strings, lists, sets, hashes, etc.)
    
- Script execution and batch operations
    
- Connection to local or remote Redis instances
    
- Support for authentication and cluster connections

---
### `Usage Basics`

- Connect to a Redis server:
    `redis-cli`
    
- Set a key:
    `SET user:1 "Franco"`
    
- Retrieve a key:
    `GET user:1`
    
- Delete a key:
    `DEL user:1`

---
### `Challenges`

- Limited to Redis systems
    
- No support for relational-style queries
    
- Memory management considerations affect behavior
    
- Advanced cluster operations may require additional configuration knowledge

---
### `Connected Notes`

- [[DB-Specific CLI Clients]]