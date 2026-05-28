
**rpm** is the **low-level package management tool** used in RPM-based Linux distributions to install, remove, query, and verify software packaged in the `.rpm` format. It operates directly on package files and the system package database.

---
### `Key Capabilities`

- **Direct Package Installation & Removal**  
    Installs and removes individual `.rpm` packages on the system.
    
- **Package Querying**  
    Lists installed packages, files, versions, and metadata.
    
- **Package Verification**  
    Verifies file integrity, checksums, and signatures of installed packages.
    
- **Script Execution**  
    Runs pre/post install, upgrade, and removal scripts embedded in packages.
    
- **Database Management**  
    Maintains the local RPM package database.

---
### `Usage Basics`

- Install a package  
    `rpm -i package.rpm`
    
- Upgrade a package  
    `rpm -U package.rpm`
    
- Remove a package  
    `rpm -e package-name`
    
- Query installed packages  
    `rpm -qa`
    
- Verify a package  
    `rpm -V package-name`

---
### `Challenges`

- **No Dependency Resolution**  
    Does not automatically fetch or resolve dependencies.
    
- **Manual Package Handling**  
    Requires users to manage repositories indirectly via higher-level tools.
    
- **Not User-Friendly Alone**  
    Typically used by administrators or internally by tools like DNF.

---
### `Connected Notes`

- [[RPM Package Ecosystem]]