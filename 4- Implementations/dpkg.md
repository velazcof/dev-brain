
**dpkg** is a **low-level package manager implementation** used by Debian-based Linux distributions. It installs, removes, and configures software packaged in the **DEB package format**, operating directly on the local system without handling repositories or dependency resolution.

---
### `Key Capabilities`

- **Direct DEB Package Handling**  
    Installs, removes, and configures `.deb` packages.
    
- **Package Database Management**  
    Maintains the local record of installed packages and their states.
    
- **Script Execution**  
    Runs package-maintainer scripts during install, upgrade, and removal.
    
- **Foundation for Higher-Level Tools**  
    Acts as the backend used by APT and other frontends.
    
- **Fine-Grained Control**  
    Allows manual intervention when higher-level tools fail.

---
### `Usage Basics`

- Install a package:
    
    - `dpkg -i package.deb`
    
- Remove a package:
    
    - `dpkg -r package_name`
    
- List installed packages:
    
    - `dpkg -l`
    
- Show package info:
    
    - `dpkg -s package_name`

---
### `Challenges`

- **No Dependency Resolution**  
    Dependencies must be handled manually or via APT.
    
- **Local-Only Scope**  
    Does not manage repositories or updates.
    
- **Error-Prone for Beginners**  
    Incorrect usage can leave packages in broken states.
    
- **Not User-Friendly**  
    Designed for system-level control rather than convenience.

---
### `Connected Notes`

- [[DEB Package Ecosystem]]