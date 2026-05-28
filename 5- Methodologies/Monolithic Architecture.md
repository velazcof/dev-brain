
**Monolithic Architecture** is a software design pattern in which all parts of an application — user interface, business logic, data access, and supporting modules — are packaged and deployed as a **single unified unit**.  

All functionality runs inside one codebase and one process.

---
### `Key Ideas`

- **Single Deployment Unit:**  
    The entire application is built, tested, and shipped together.  
    _Common in early-stage projects where deployment simplicity is essential._
    
- **Shared Resources & Memory:**  
    Components run in the same runtime, often sharing one database and memory space.  
    _Useful when tight integration and fast internal communication are required._
    
- **Straightforward Development (Initially):**  
    A simple architecture that small teams can iterate on quickly.  
    _Ideal for small apps, internal tools, or MVPs._
    
- **Tight Coupling Over Time:**  
    Modules often become interdependent, making isolated updates difficult.
    
- **Scales Vertically, Not Horizontally:**  
    You typically scale by running **more copies of the entire app**, not individual pieces.
    
- **Technology Lock-In:**  
    Replacing frameworks or modernizing internals becomes costly once the monolith grows.

---
### `Challenges`

- Difficult to scale individual features independently.
- Large deployments cause slow releases and riskier updates.
- Refactoring becomes harder as the codebase grows and coupling increases.
- Hard to adopt new technologies without major rewrites.
- Testing can become slow due to the size of the system.

---
### `Connected Notes`

- [[Architectural Patterns]]