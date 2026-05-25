
### `Definition`

The **RPM Package Ecosystem** is the software packaging and distribution framework used by Red Hat–style Linux systems. It centers around the **`.rpm` package format**, the **RPM Package Manager**, and higher-level tools like **DNF**, **YUM**, and various GUI package managers.

---
### `Key Ideas`

- **`.rpm` Package Format**  
    Contains binaries, metadata, versioning info, and pre/post-install scripts.
    
- **RPM (Low-Level Tool)**  
    Installs, removes, verifies, and queries packages _without_ dependency resolution.
    
- **DNF (High-Level Manager)**  
    Modern replacement for YUM, handles dependency solving, repositories, upgrades, and transactions.
    
- **YUM (Legacy Manager)**  
    Older package manager still found in some distributions; many commands are now symlinked to DNF.
    
- **Graphical Frontends**  
    Tools like **PackageKit** and **YaST** offer GUI package management on RPM-based systems.
    
- **Repository-Based Delivery**  
    Software is distributed through cryptographically signed repos maintained by RHEL, Fedora, SUSE, and community projects.

---
### `Connected Notes`

- [[Linux Package Management]]
- [[RPM Package Format (.rpm)]]
- [[rpm]]
- [[DNF]]
- [[PackageKit]]
- [[YaST]]