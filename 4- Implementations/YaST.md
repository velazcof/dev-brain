
**YaST (Yet another Setup Tool)** is a **system administration tool** used in SUSE-based Linux distributions to configure and manage system components through a unified interface.  

It provides both **graphical and text-based** tools for administering packages, users, services, networking, storage, and system settings.

---
### `Key Capabilities`

- **Centralized System Configuration**  
    Manages users, groups, networking, storage, bootloader, services, and security settings.
    
- **Package Management Integration**  
    Interfaces with RPM-based package management tools (via `zypper` and related backends).
    
- **Modular Design**  
    Configuration areas are split into modules (e.g. software, hardware, system, network).
    
- **GUI and TUI Support**  
    Available as a graphical application and as a terminal-based interface.
    
- **Distribution-Specific Automation**  
    Tailored tightly to openSUSE and SUSE Linux Enterprise systems.

---
### `Usage Basics`

- Launch graphical YaST  
    `yast2`
    
- Launch text-based YaST  
    `yast`
    
- Open a specific module  
    `yast users`  
    `yast network`

---
### `Challenges`

- **Distro-Specific**  
    Only relevant to SUSE-based systems.
    
- **Limited Transferability**  
    Concepts do not generalize well to other Linux distributions.
    
- **CLI Alternatives Exist**  
    Many tasks can be performed directly via command-line tools and config files.

---
### `Connected Notes`

- [[RPM Package Ecosystem]]