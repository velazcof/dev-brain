
**Fish (Friendly Interactive SHell)** is a **modern Unix shell** designed primarily for **interactive use**, focusing on **usability, discoverability, and sensible defaults** rather than strict POSIX compatibility.

It aims to work well **out of the box** with minimal configuration.

---
### `Key Capabilities`

- **User-Friendly by Default**
    
    - Automatic command suggestions based on history
    - Syntax highlighting as you type
    - Clear, readable error messages
    
- **Strong Interactive Experience**
    
    - Powerful tab completion with descriptions
    - Intuitive navigation and keybindings
    - Designed to reduce the need for memorization
    
- **Modern Configuration Model**
    
    - Uses a structured, readable syntax
    - Web-based configuration tool (`fish_config`)
    - No need for complex startup files to be productive
    
- **Isolated from POSIX Constraints**
    
    - Purposefully diverges from POSIX shell syntax
    - Cleaner, more consistent language design choices
    
- **Developer-Oriented Daily Shell**
    
    - Popular as a login shell for developers
    - Often used alongside Bash or `sh` for scripting

---
### `Usage Basics`

`fish`

**Shebang example:**

`#!/usr/bin/env fish`

---
### `Challenges`

- **Not POSIX-Compatible**  
    Fish scripts are not portable to `sh`, Bash, or Zsh.
    
- **Limited for System Scripting**  
    Rarely used for init or system-level scripts.
    
- **Smaller Scripting Ecosystem**  
    Fewer existing scripts and examples compared to Bash.

---
### `Connected Notes`

- [[Linux Shells]]