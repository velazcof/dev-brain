
### `Definition`

**Hardware abstraction** is the mechanism through which the operating system **hides hardware-specific details** and exposes uniform interfaces to higher system layers. It allows software to operate independently of the underlying physical hardware.

---
### `How It Works`

The kernel mediates all direct hardware access by translating generic operations into hardware-specific instructions.

Device-specific behavior is encapsulated behind standardized interfaces so that higher layers interact with abstract representations rather than raw hardware.

This separation ensures that changes in hardware do not require changes in application or system-level software.

---
### `Why It Exists`

- To enable **portability** across different hardware platforms
- To isolate software from hardware complexity
- To simplify system design and development
- To allow hardware evolution without breaking software
- To enforce controlled and secure hardware access

---
### `Connected Notes`

- [[Kernel Responsibilities]]