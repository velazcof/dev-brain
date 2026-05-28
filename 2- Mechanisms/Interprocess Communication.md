
**Interprocess communication (IPC)** is the mechanism that allows **separate processes to exchange data and coordinate execution** while remaining isolated from one another. It enables cooperation between independently running programs.

---
### `How It Works`

The operating system provides controlled channels through which processes can send data, signals, or synchronization events. These channels mediate communication without allowing direct memory access between processes.

IPC mechanisms manage data transfer, synchronization, and access control, ensuring messages are delivered safely and consistently across process boundaries.

---
### `Why It Exists`

- To enable **coordination between isolated processes**
    
- To allow complex systems to be composed of multiple cooperating programs
    
- To preserve **process isolation and security**
    
- To support client–server models and modular system design
    
- To enable parallelism without shared memory corruption

---
### `Connected Notes`

- [[Kernel Responsibilities]]