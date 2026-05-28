
The **XNU Kernel** is the **core operating system kernel** used by **Apple operating systems**, including **macOS, iOS, iPadOS, watchOS, and tvOS**.

It is a **hybrid kernel** that combines components from **Mach** and **BSD**, forming the low-level foundation of Apple’s OS platforms.

---
### `Key Ideas`

- **Hybrid Kernel Architecture**  
    XNU blends:
    
    - **Mach** (processes, threads, IPC, virtual memory)
    - **BSD** (POSIX APIs, filesystems, networking, permissions)
    - **I/O Kit** (object-oriented driver framework)
    
- **Mach-Based Core**  
    Uses Mach concepts such as:
    
    - Tasks and threads
    - Message-based inter-process communication (IPC)
    - Advanced virtual memory management
    
- **BSD Userland Integration**  
    Provides a full **Unix/POSIX environment** via BSD layers, enabling:
    
    - Standard Unix system calls
    - Familiar permissions and process model
    - Compatibility with Unix tooling
    
- **I/O Kit for Drivers**  
    Device drivers are implemented using **I/O Kit**, which:
    
    - Is written largely in C++
    - Runs mostly in kernel space
    - Emphasizes stability and modularity
    
- **Security & Isolation Focus**  
    Enforces strong separation between:
    
    - User space and kernel space  
        and supports modern security mechanisms used across Apple platforms.
    
- **Single Kernel, Multiple Platforms**  
    The same XNU kernel architecture underpins all Apple OSes, adapted for:
    
    - Desktop
    - Mobile
    - Embedded environments

---
### `Use Cases`

- Core kernel for **macOS** desktop operating systems
    
- Kernel foundation for **iOS and iPadOS**
    
- Supporting Apple’s tightly integrated hardware–software ecosystem
    
- Providing a Unix-based kernel with strong security and performance guarantees
    
- Enabling consistent OS behavior across Apple device families

---
### `Connected Notes`

- [[Kernel Implementations]]