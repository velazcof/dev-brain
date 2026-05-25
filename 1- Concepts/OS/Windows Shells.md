
### `Definition`

**Windows shells** are **command-line environments** used to interact with the Windows operating system, differing significantly from Unix shells in design and philosophy.

---
### `Key Ideas`

- **Native Windows Shell Model**  
    Windows shells are not POSIX-based and use different execution and scripting models.
    
- **Commonly Encountered Shells**
    
    - **PowerShell (`pwsh`)** — modern, object-based default shell
    - **Command Prompt (`cmd.exe`)** — legacy text-based shell
    
- **Unix-Like Shells via Compatibility Layers**
    
    - **Bash (WSL)** — full Linux shell environment inside Windows
    - **Git Bash** — minimal Unix-like shell bundled with Git
    
- **Object vs Text Pipeline**  
    PowerShell passes structured objects between commands, unlike Unix shells which pass text streams.

---
### `Connected Notes`

- [[Windows User Space]]
- [[PowerShell]]
- [[Command Prompt]]