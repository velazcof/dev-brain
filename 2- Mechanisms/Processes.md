
A **process** represents a **running instance of a program**, encompassing its execution state, allocated resources, and isolation boundaries within an operating system. It is the fundamental unit through which work is executed and managed.

---
### `How It Works`

When a program is started, the operating system creates a process by loading the program code and initializing its execution context.  

The process maintains state such as registers, memory regions, and resource handles while it runs.

The operating system scheduler selects processes (or their threads) to receive CPU time, and controlled transitions into privileged execution occur when the process requests system services.

---
### `Why It Exists`

- To enable **concurrent execution** of multiple programs
    
- To provide **isolation and protection** between running workloads
    
- To manage **resource allocation and scheduling**
    
- To support structured program lifecycles and execution control

---
### `Connected Notes`

- [[Operating System (OS)]]