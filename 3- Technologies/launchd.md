
**launchd** is the **system initialization and service management daemon** used by macOS to manage system startup, background services, scheduled jobs, and user agents. It is the first process started by the system and remains responsible for managing services throughout runtime.

---
### `Key Capabilities`

- **System Initialization**  
    Boots the system by starting core services and daemons.
    
- **Service & Job Management**  
    Starts, stops, restarts, and monitors background processes (daemons and agents).
    
- **On-Demand Execution**  
    Launches services only when needed (e.g. when a socket, file, or event is triggered).
    
- **Unified Scheduling Model**  
    Replaces traditional Unix tools like `init`, `cron`, and `at` with a single framework.
    
- **User and System Scopes**  
    Manages both system-wide services and per-user background processes.

---
### `Usage Basics`

- List loaded jobs  
    `launchctl list`
    
- Load a job definition  
    `launchctl load <plist>`
    
- Unload a job  
    `launchctl unload <plist>`
    
- Manage jobs (modern syntax)  
    `launchctl bootstrap`  
    `launchctl bootout`

---
### `Challenges`

- **macOS-Specific**  
    Not portable to other Unix-like systems.
    
- **Complex Configuration Format**  
    Uses XML property lists (`.plist`), which can be verbose and error-prone.
    
- **Different Mental Model**  
    Event-driven and on-demand execution differs from traditional init systems.

---
### `Connected Notes`

- [[macOS User Space]]