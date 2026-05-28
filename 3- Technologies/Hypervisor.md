
A **Hypervisor** is a software or firmware layer that **creates and manages virtual machines (VMs)** by dividing and allocating a host’s hardware resources — CPU, memory, storage, and networking — across multiple isolated environments.

---
### `Key Ideas`

- **Resource manager** → Controls and monitors the use of hardware among VMs, ensuring efficient sharing and isolation.
    
- **Two main types:**
    
    - **Type 1 (Bare Metal)** → Runs directly on the hardware. High performance and used in enterprise virtualization (e.g., VMware ESXi, Microsoft Hyper-V, Xen).
        
    - **Type 2 (Hosted)** → Runs on top of an existing OS (e.g., VirtualBox, VMware Workstation). Easier to use but less efficient.
        
- **Security isolation** → Prevents VMs from accessing each other’s data or processes.
    
- **Core enabler** → The foundation of virtual machines and cloud infrastructure.

---
### `Use Cases`

- Running multiple OS environments on a single host for testing or development.
    
- Server consolidation to reduce hardware costs.
    
- Enabling virtual data centers and IaaS platforms.
    
- Creating sandboxed environments for malware analysis or secure experimentation.

---
### `Connected Notes`

- [[Virtualization]]
- [[Virtual Machines (VMs)]]
- [[Type 1 Hypervisor]]
- [[Type 2 Hypervisor]]