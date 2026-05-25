
### `Definition`

The **Pacman Package Ecosystem** is the software packaging and distribution framework used by **Arch Linux** and Arch-based distributions. It revolves around the **pacman package manager**, the **PKG package format**, and the ability to extend software availability through the **Arch User Repository (AUR)**.

---
### `Key Ideas`

- **PKG Package Format**  
    Packages are distributed as compressed archives (`.pkg.tar.zst`) containing binaries, metadata, and install scripts.
    
- **Pacman (Low-Level + High-Level Manager)**  
    The pacman CLI performs installation, updates, integrity checks, and dependency resolution.
    
- **Rolling Release Philosophy**  
    Designed for continuous updates rather than major version upgrades.
    
- **AUR Integration (Indirect)**  
    Although pacman does not directly access the AUR, the ecosystem supports it through **AUR helpers** that interface with pacman.
    
- **Simple Repository Structure**  
    Follows Arch’s KISS principle with clear, minimal repos:
    
    - core
    - extra
    - community
    - multilib (optional)
    
- **Build-from-Source Flexibility**  
    Users can compile software using **PKGBUILD scripts**, enabling customization and transparency.

---
### `Connected Notes`

- [[Linux Package Management]]
- [[Pacman]]
- [[PKG Package Format]]
- [[AUR]]