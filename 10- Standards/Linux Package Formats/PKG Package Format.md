
The **PKG package format** defines the **structure and layout of software packages** used by the pacman package manager in Arch-based Linux distributions. It specifies how software, metadata, and installation scripts are bundled for distribution and installation.

---
### `Purpose`

- To provide a **consistent, machine-readable format** for distributing software.
    
- To allow package managers to **install, upgrade, and remove software reliably**.
    
- To define a **contract** between package builders, repositories, and the package manager.
    
- To ensure dependency information and installation behavior are standardized.

---
### `Structure`

A PKG package is a compressed archive containing:

- **Package metadata**
    
    - name, version, description
    - dependencies and conflicts
    - architecture and license information
    
- **Filesystem payload**
    
    - binaries, libraries, configuration files placed in system paths
    
- **Installation scripts (optional)**
    
    - pre-install
    - post-install
    - pre-remove
    - post-remove
    
- **Checksums and signatures**
    
    - used for integrity verification and trust

The format itself does **not define how packages are built**, only how they are **packaged and consumed**.

---
### `Connected Notes`

- [[Pacman Package Ecosystem]]