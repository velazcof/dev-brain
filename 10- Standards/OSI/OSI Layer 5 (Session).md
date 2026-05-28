
The **Session Layer (Layer 5)** of the **OSI Model** defines how **communication sessions** are established, maintained, and terminated between applications.  
It manages the **dialogue control** between systems — deciding who transmits, when, and for how long.

---
### `Purpose`

- Establishes and synchronizes **logical connections** (sessions) between applications.
    
- Handles **session setup, management, and teardown** to ensure orderly data exchange.
    
- Provides **checkpointing and recovery** so communication can resume after interruptions.
    
- Coordinates **full-duplex, half-duplex, or simplex** transmission modes.
    
- Enables consistent, managed communication for long-lived interactions (e.g., remote logins, file transfers).

---
### `Structure`

|Aspect|Function|Examples|
|---|---|---|
|**Session Establishment**|Initiates and negotiates communication parameters.|Authentication, handshake sequences|
|**Dialog Control**|Manages who transmits when; supports full- or half-duplex modes.|NetBIOS, RPC|
|**Synchronization**|Inserts checkpoints for recovery in long data transfers.|File transfer resume points|
|**Session Termination**|Gracefully closes the connection.|“Goodbye” signals, FIN messages (in TCP context)|

**Data Unit:** _Data / Messages (session frames)_  
**Devices / Components:** Gateways, session managers, API middleware.

---
### `Connected Notes`

- [[OSI Model]]
- [[OSI Layer 4 (Transport)]]
- [[OSI Layer 6 (Presentation)]]
- [[Remote Procedure Calls (RPC)]]
- [[Authentication and Session Management]]
- [[Connection Establishment and Termination]]