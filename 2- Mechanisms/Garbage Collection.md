
**Garbage collection** is the process by which a runtime system **automatically reclaims memory** that is no longer reachable or needed by a program, preventing memory leaks and reducing manual memory management.

---
### `How It Works`

- The runtime tracks **object references** created during execution.
- Objects that are **no longer reachable** from active references are identified as garbage.
- A collection cycle reclaims the memory used by those objects.
- Common strategies include:
    - tracing reachability from roots (e.g., stack, globals)
    - periodic or incremental collection
- Collection may pause execution briefly or run concurrently, depending on the system.

---
### `Why It Exists`

- To **simplify memory management** for developers.
- To **prevent memory leaks** and dangling references.
- To improve **program safety and reliability**.
- To enable higher-level programming models without explicit deallocation.
- To manage memory efficiently in long-running applications.

---
### `Connected Notes`

- [[Memory & References]]