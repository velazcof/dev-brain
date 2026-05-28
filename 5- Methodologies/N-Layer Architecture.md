
**Layered Architecture** organizes a software system into distinct layers — such as presentation, business logic, and data access — where each layer has a focused responsibility and communicates only with its adjacent layers.  

It is one of the most widely used architectural patterns in enterprise systems.

---
### `Key Ideas`

- **Clear Separation of Concerns:**  
    Each layer has a specific purpose (UI, domain logic, persistence).  
    _Useful for maintainability, long-term evolution, and teamwork._
    
- **Predictable Dependency Flow:**  
    Requests move vertically from the UI → Logic → Data layers.  
    _Makes code easier to understand and test._
    
- **Modular Structure Within a Single System:**  
    Works for both monolithic and distributed systems.  
    _Often used inside monoliths to keep code organized._
    
- **Supports Standard Enterprise Development:**  
    Fits teams working with well-defined roles (UI devs, backend devs, DB devs).  
    _Common in business apps, corporate systems, and APIs._
    
- **Testability & Structure:**  
    Layers enable unit and integration testing with clear boundaries.
    
- **In Practice:**
	- **2-layer** (UI ↔ DB)
	    
	- **3-layer** (Presentation ↔ Business Logic ↔ Data Access)
	    
	- **4-layer** (UI ↔ Application Layer ↔ Domain Layer ↔ Infrastructure Layer)
	    
	- **N-layer** (whatever the system requires)

---
### `Challenges`

- Too rigid when layers are enforced strictly.
    
- “Layer leakage” can occur when logic ends up in the wrong layers.
    
- Business logic layer can become bloated over time.
    
- Scaling limitations if implemented as part of a monolithic architecture.
    
- Slower development when simple tasks must pass through multiple layers.

---
### `Connected Notes`

- [[Architectural Patterns]]