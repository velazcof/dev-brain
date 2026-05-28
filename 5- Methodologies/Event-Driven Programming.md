
**Event-Driven Programming** is a programming paradigm where program flow is driven by **events**—such as user actions, messages, or system signals—rather than by a predefined, linear execution sequence.

---
### `Key Ideas`

- **Event-Centric Flow**  
    Execution occurs in response to events instead of following a fixed order.
    
- **Event Producers & Consumers**  
    One part of the system emits events, while others react to them.
    
- **Handlers / Listeners**  
    Events are processed by registered handlers that encapsulate reaction logic.
    
- **Loose Coupling**  
    Components do not need direct knowledge of each other, only of events.
    
- **Asynchronous by Nature**  
    Event handling often happens asynchronously, improving responsiveness.
    
- **Common in Reactive Systems**  
    Widely used in GUIs, web applications, distributed systems, and messaging systems.

---
### `Challenges`

- **Control Flow Complexity**  
    Execution order can be hard to reason about or trace.
    
- **Debugging Difficulty**  
    Bugs may arise from timing issues or unexpected event sequences.
    
- **Hidden Dependencies**  
    Relationships between components can become implicit.
    
- **Event Overload**  
    Poorly designed systems may generate excessive or redundant events.
    
- **State Management**  
    Managing shared state across asynchronous handlers can be complex.

---
### `Connected Notes`

- [[Programming Paradigms]]