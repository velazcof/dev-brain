
**PowerShell** is a **command-line shell and scripting environment** developed by Microsoft, designed for **task automation, system administration, and configuration management**, especially on Windows but also cross-platform.

It is used when you need **structured automation**, deep system access, or object-based command pipelines.

---
### `Key Capabilities`

- **Object-based pipeline**  
    Commands pass rich objects (not plain text), enabling powerful composition and filtering.
    
- **Powerful scripting language**  
    Supports variables, functions, modules, conditionals, loops, and error handling.
    
- **Deep system integration**  
    Native access to Windows components, system APIs, services, registry, and .NET.
    
- **Cross-platform support**  
    PowerShell Core runs on Windows, Linux, and macOS.
    
- **Extensible module system**  
    Large ecosystem of modules for cloud, networking, security, and automation tasks.

---
### `Usage Basics`

- Launch the shell:
    
    - `powershell` (Windows PowerShell)
    - `pwsh` (PowerShell Core)
    
- Run a command:
    
    - `Get-Process`
    
- Pipeline example:
    
    - `Get-Service | Where-Object {$_.Status -eq "Running"}`
    
- Run a script:
    
    - `./script.ps1`

---
### `Challenges`

- **Steep learning curve** compared to traditional text-based shells
    
- **Verbosity** in command naming
    
- **Version differences** between Windows PowerShell (5.1) and PowerShell Core (7+)
    
- **Execution policy restrictions** may block scripts by default
    
- Less idiomatic on Unix systems compared to Bash/Zsh

---
### `Connected Notes`

- [[Windows Shells]]