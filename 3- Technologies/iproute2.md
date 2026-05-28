
**iproute2** is a **Linux networking configuration and management technology** that provides user-space tools to control and inspect the kernel’s networking stack. It replaces legacy networking utilities with a modern, unified interface.

---
### `Key Ideas`

- **Kernel Networking Interface**  
    Interacts directly with Linux kernel networking subsystems via Netlink.
    
- **Modern Networking Toolset**  
    Provides commands such as `ip`, `ss`, and `tc` for managing interfaces, routes, addresses, and traffic control.
    
- **Replaces Legacy Tools**  
    Supersedes older utilities like `ifconfig`, `route`, and `netstat`.
    
- **Unified Command Model**  
    Uses a consistent syntax for managing links, addresses, routes, and network state.
    
- **Essential for Advanced Networking**  
    Required for namespaces, containers, routing rules, and traffic shaping.

---
### `Use Cases`

- Network interface configuration
    
- IP addressing and routing management
    
- Network namespaces and container networking
    
- Traffic control and bandwidth shaping
    
- Diagnosing network connections and sockets

---
### `Connected Notes`

- [[Linux Utilities]]