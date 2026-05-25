### `Definition`

A **kernel** is the **core component of an operating system** responsible for managing hardware resources and enabling communication between software applications and the underlying hardware. It acts as the bridge between user programs and the system’s physical components (CPU, memory, storage, devices).

---
### `Key Ideas`

- **Resource Manager:**  
    The kernel allocates CPU time, memory, and I/O resources to processes.
    
- **Hardware Abstraction:**  
    Provides a unified interface so applications don’t need to know hardware details.
    
- **System Calls:**  
    Exposes functions (APIs) that user applications call to perform privileged actions (read files, allocate memory, create processes).
    
- **Process & Thread Handling:**  
    Schedules tasks, switches between processes, and enforces multitasking.
    
- **Memory Management:**  
    Controls physical and virtual memory, paging, and protection boundaries.
    
- **Device Drivers:**  
    Integrates hardware through pluggable drivers managed by the kernel.
    
- **Security & Isolation:**  
    Enforces permissions, process isolation, and safe access to hardware resources.
    
- **Kernel Modes:**  
    Operates in **privileged mode** (kernel space) while applications run in **user space** for safety and stability.

---
### `Connected Notes`

- [[Operating System (OS)]]
- [[Kernel Implementations]]
- [[Kernel Responsibilities]]

