
**DNF (Dandified YUM)** is a **high-level package management tool** for RPM-based Linux distributions.  
It installs, updates, and removes software packages from repositories while automatically resolving dependencies.

---
### `Key Capabilities`

- **Automatic Dependency Resolution**  
    Resolves and installs required dependencies for RPM packages reliably.
    
- **Repository-Based Management**  
    Fetches packages from configured remote repositories.
    
- **Transaction Safety**  
    Applies package operations as transactions to reduce system inconsistency.
    
- **Performance Improvements**  
    Faster metadata handling and dependency resolution compared to YUM.
    
- **rpm Integration**  
    Uses `rpm` as the underlying low-level package manager.

---
### `Usage Basics`

- Install a package  
    `dnf install <package>`
    
- Remove a package  
    `dnf remove <package>`
    
- Upgrade system packages  
    `dnf upgrade`
    
- Search for packages  
    `dnf search <name>`
    
- List installed packages  
    `dnf list installed`

---
### `Challenges`

- **RPM-Based Only**  
    Not usable on DEB- or APK-based systems.
    
- **CLI-Oriented**  
    Not designed as a graphical tool (often paired with PackageKit for GUIs).
    
- **Learning Curve for New Users**  
    More options and flags than simpler package managers.

---
### `Connected Notes`

- [[RPM Package Ecosystem]]