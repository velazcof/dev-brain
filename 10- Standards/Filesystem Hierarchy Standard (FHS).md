
The **Filesystem Hierarchy Standard (FHS)** defines a **standard directory structure and naming conventions** for Unix-like operating systems, specifying where files and directories should be located in the filesystem.

It establishes a common layout for system files, user data, and application resources.

---
### `Purpose`

- To ensure **consistency and predictability** across Unix-like systems
    
- To allow software to run correctly regardless of distribution
    
- To simplify system administration and troubleshooting
    
- To enable interoperability between distributions, packages, and tools
    
- To separate system-managed files from user-managed data

---
### `Structure`

The standard defines the roles of top-level directories, including:

- `/` — root of the filesystem
    
- `/bin`, `/sbin` — essential system binaries
    
- `/lib`, `/lib64` — shared libraries
    
- `/etc` — system configuration files
    
- `/usr` — user-space applications and read-only data
    
- `/var` — variable data (logs, caches, spools)
    
- `/home` — user home directories
    
- `/tmp` — temporary files

Each directory has a **well-defined purpose**, restricting what types of files may be placed there.

---
### `Connected Notes`

- [[Linux User Space]]