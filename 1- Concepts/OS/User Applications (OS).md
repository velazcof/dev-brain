
### `Definition`

**User applications** are programs that run in user space and provide functionality directly to the end user, such as web browsers, editors, office suites, communication tools, and media players. They rely on OS services but operate independently from system-level components.

---
### `Key Ideas`

- **Run entirely in user space**, without kernel privileges.
    
- Provide direct interaction and productivity features for users.
    
- Built on top of:
    
    - system libraries
    - window managers or desktop environments (GUI apps)
    - shells/terminals (CLI apps)
    
- Can be:
    
    - **CLI applications** (e.g., Vim, Git, Curl)
    - **GUI applications** (e.g., Firefox, VS Code, LibreOffice)
    
- Installed via:
    
    - OS package managers (apt, dnf, pacman, winget, Homebrew)
    - Language package managers (pip, npm, etc.)
    - Standalone installers or app stores
    
- Do not interact with hardware directly — communication is mediated by the OS/kernel.

---
### `Connected Notes`

- [[User Space Components (OS)]]