
### `Definition`

**User Space** is the portion of an operating system where **applications and non-privileged processes run**, separated from the kernel for safety and stability. Programs in user space interact with hardware and kernel services **indirectly**, typically through system calls, libraries, and runtime environments.

---
### `Key Ideas`

- **Separation from the Kernel**  
    User space cannot directly access hardware or privileged memory.  
    This prevents application bugs from crashing the system.
    
- **Application Execution Environment**  
    All user programs—GUIs, CLI tools, shells, services—run here.
    
- **Libraries & Runtime Environments**  
    User space includes shared libraries (like glibc), runtime systems (Python, JVM), and frameworks that applications depend on.
    
- **System Call Boundary**  
    User space interacts with the kernel via system calls, which act as the gateway to hardware, files, networking, and process management.
    
- **Crash Containment**  
    If a user-space process fails, the kernel remains unaffected, enabling strong OS reliability.
    
- **Different per OS Family**
    - **Linux:** GNU coreutils, shells, package managers, systemd, desktop environments
    - **Windows:** Win32 API, .NET runtime, Windows Shell (Explorer)
    - **macOS:** POSIX tools + Cocoa frameworks
    
- **Customizable and Replaceable**  
    Unlike the kernel, user space can vary dramatically between distributions or OS variants.

---
### `Connected Notes`

- [[Operating System (OS)]]
- [[User Space Components (OS)]]
- [[Windows User Space]]
- [[macOS User Space]]
- [[Linux User Space]]