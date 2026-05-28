
The **DEB package format** defines the **structure and conventions** for software packages used by Debian-based Linux distributions. It specifies how application files, metadata, and maintenance scripts are bundled for installation and management by package tools.

---
### `Purpose`

- To provide a **standardized way to distribute software** across Debian-based systems.
    
- To enable package managers to **install, upgrade, configure, and remove software reliably**.
    
- To define a **clear contract** between package builders, repositories, and management tools.
    
- To support dependency declaration, versioning, and system integration.

---
### `Structure`

A DEB package is an archive composed of:

- **Control metadata**
    
    - package name, version, architecture
    - dependencies, conflicts, recommendations
    - maintainer and description
    
- **Filesystem payload**
    
    - binaries, libraries, configuration files placed in standard paths
    
- **Maintainer scripts (optional)**
    
    - `preinst`, `postinst`
    - `prerm`, `postrm`
    
- **Checksums and signatures**
    
    - used for integrity and authenticity verification

The format defines **how packages are packaged**, not how repositories or dependency resolution work.

---
### `Connected Notes`

- [[DEB Package Ecosystem]]