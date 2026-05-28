
**Language Package Managers** are tools that manage **project-level code dependencies** for programming languages. They install libraries, handle versioning, manage lock files, and ensure reproducible builds.

---
### `Key Ideas`

- **Dependency Installation & Resolution**  
    Automatically downloads libraries and resolves dependency trees.
    
- **Version Management**  
    Uses lock files (e.g., `package-lock.json`, `Pipfile.lock`) for reproducibility.
    
- **Registry Integration**  
    Connects to language-specific repositories such as:
    
    - npm registry
    - PyPI
    - Maven Central
    - crates.io
    - RubyGems
    
- **Project Isolation**  
    Supports local installs, virtual environments, or workspace-level installs.
    
- **Scripting & Build Integration**  
    Many package managers also provide task runners (npm scripts, Maven lifecycles).

---
### `Use Cases`

- Installing third-party libraries for a project.
- Ensuring dependency versions match across team members.
- Publishing reusable code modules.
- Automating build, test, and deploy phases through integrated scripts.

---
### `Connected Notes`

- [[Package Management]]
- [[Packages]]
- [[Build Tools]]