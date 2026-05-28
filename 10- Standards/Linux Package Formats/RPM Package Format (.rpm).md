
The **RPM package format (.rpm)** defines the **structure, metadata, and behavior** of software packages used by RPM-based Linux distributions. It specifies how software, dependencies, scripts, and verification data are packaged for installation and management.

---

### `Purpose`

- To provide a **standardized format** for packaging and distributing software.
    
- To enable **reliable installation, upgrade, and removal** of system and application packages.
    
- To support **dependency tracking**, integrity verification, and lifecycle scripting.
    
- To act as a **formal contract** between package repositories and package management tools.

---
### `Structure`

An `.rpm` file consists of several structured components:

- **Header**
    
    - package name, version, release
    - architecture
    - dependencies and conflicts
    - scripts (pre/post install, upgrade, remove)
    
- **Payload**
    
    - compressed archive containing binaries, libraries, and configuration files
    
- **Signatures**
    
    - cryptographic signatures and checksums
    - used for integrity and authenticity verification
	
- **Key characteristics**
	
	- Binary package format (not plain tar)
	- Supports script hooks at multiple lifecycle stages
	- Strong verification and dependency metadata
	- Architecture-specific by default

---
### `Connected Notes`

- [[RPM Package Ecosystem]]