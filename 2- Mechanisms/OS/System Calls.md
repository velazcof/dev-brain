
**System calls** define how **user-space programs request services from the operating system kernel** in a controlled and safe manner. They provide the formal interface through which applications access core operating system functionality.

---
### `How It Works`

When a program needs an operation that requires kernel privileges, it invokes a system call.  

Execution transitions from user space into kernel space, where the request is validated and performed.

After completion, control is returned to user space along with the result of the operation.  
This transition enforces isolation while allowing necessary interaction with system resources.

---
### `Why It Exists`

- To enable **safe access** to privileged operating system functionality
- To enforce **isolation and protection** between applications and the kernel
- To provide a consistent interface to processes, memory, files, and devices
- To abstract hardware and kernel internals from user-space programs

---
### `Connected Notes`

- [[Operating System (OS)]]
- [[Kernel Responsibilities]]