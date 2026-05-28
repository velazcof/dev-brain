
A **file system** is the mechanism that defines how data is **organized, stored, named, and accessed** on persistent storage devices. It provides a structured way for the operating system to manage files and directories independently of the underlying hardware.

---
### `How It Works`

The file system maps human-readable paths and filenames to physical storage locations. It tracks metadata such as size, permissions, ownership, and timestamps, and coordinates read/write operations through the kernel.

By abstracting raw storage blocks into files and directories, it enables consistent data access while handling allocation, lookup, and integrity concerns.

---
### `Why It Exists`

- To provide a **persistent data model** beyond program execution
- To organize data in a **hierarchical and manageable structure**
- To abstract low-level storage details
- To enforce **access control and permissions**
- To support reliable data retrieval and modification

---
### `Connected Notes`

- [[Kernel Responsibilities]]