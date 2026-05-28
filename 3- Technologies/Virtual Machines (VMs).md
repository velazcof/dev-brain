
A **Virtual Machine (VM)** is a **software-based simulation of a physical computer** that runs its own operating system and applications independently of the host machine. Multiple VMs can share the same physical hardware through a hypervisor, which manages and isolates them.

---
### `Key Ideas`

- **Hardware abstraction** → A VM emulates a full hardware system (CPU, memory, storage) using software.
    
- **Isolation** → Each VM runs separately, providing security and stability between environments.
    
- **Hypervisor** → The layer that enables virtualization, allocating system resources and managing VMs (e.g., VMware, Hyper-V, KVM).
    
- **Efficiency trade-off** → VMs are more resource-heavy than containers since each runs a full OS.
    
- **Use cases** → Testing environments, running multiple OSes on one machine, cloud hosting, and legacy system support.
    
- **Step in evolution** → Represents the bridge between physical servers and containerized workloads in modern infrastructure.

---
### `Connected Notes`

- [[Infrastructure]]
- [[Hypervisor]]