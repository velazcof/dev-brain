
**Bash (Bourne Again SHell)** is a widely used Unix shell and scripting language, developed as a GNU-compatible replacement for the original Bourne shell (`sh`)**.

It is the **default shell on most Linux distributions** and is commonly used for **interactive command-line work and system scripting**.

---
### `Key Capabilities`

- **POSIX-Compatible with Extensions**  
    Implements the POSIX shell specification while adding powerful extensions beyond `sh`.
    
- **Strong Scripting Support**  
    Supports:
    
    - Variables and environment handling
    - Conditionals and loops
    - Functions
    - Command substitution
    - Extensive string and array manipulation
    
- **Interactive Features**
    
    - Command history
    - Tab completion
    - Job control
    - Aliases and shell functions
    
- **Ubiquity and Compatibility**  
    Available by default on:
    
    - Most Linux distributions
    - macOS (older version)
    - Many Unix-like systems
    
- **System Integration**  
    Commonly used for:
    
    - System scripts
    - Init and service scripts
    - Automation and provisioning tasks

---
### `Usage Basics`

`bash`

**Common examples:**

`bash script.sh`

`#!/usr/bin/env bash`

---
### `Challenges`

- **Version Differences**  
    macOS ships an older Bash version due to licensing constraints.
    
- **Non-POSIX Features Reduce Portability**  
    Bash-specific extensions can break scripts intended for `sh`.
    
- **Less Polished Interactive UX Compared to Zsh**  
    Requires configuration for advanced completions and prompts.

---
### `Connected Notes`

- [[Linux Shells]]
- [[macOS Shells]]
- [[Bash Built-ins Ref]]
- [[Bash Syntax Ref]]