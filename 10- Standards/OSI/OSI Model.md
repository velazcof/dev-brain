
The **Open Systems Interconnection (OSI) Model** is a **networking standard** defined by the **International Organization for Standardization (ISO)**.

It establishes a **seven-layer framework** that standardizes how different systems communicate over a network, ensuring interoperability between hardware and software from different vendors.

---
### `Purpose`

- Provides a **universal reference model** for understanding and designing network systems.
    
- **Separates concerns** by dividing communication into clear functional layers, each with specific responsibilities.
    
- Enables **compatibility and modularity**, allowing different technologies and protocols to work together.
    
- Serves as a **teaching and troubleshooting framework**, helping engineers isolate issues by layer (e.g., “Layer 3 issue” = routing).

---
### `Structure`

|#|Layer|Core Function|Common Protocols / Devices|
|---|---|---|---|
|7|**Application**|Interfaces directly with user applications|HTTP, DNS, SMTP|
|6|**Presentation**|Data formatting, compression, encryption|SSL/TLS, JPEG|
|5|**Session**|Manages sessions and maintains communication state|NetBIOS, RPC|
|4|**Transport**|Reliable data delivery and flow control|TCP, UDP|
|3|**Network**|Logical addressing and routing across networks|IP, ICMP, Routers|
|2|**Data Link**|Frame transmission and MAC addressing|Ethernet, VLAN, Switches|
|1|**Physical**|Transmission of bits over hardware mediums|Cables, Hubs, Fiber|

Each layer **communicates with its peer** on another device and provides services to the layer above it.

---
### `Connected Notes`

- [[OSI Layer 1 (Physical)]]
- [[OSI Layer 2 (Data Link)]]
- [[OSI Layer 3 (Network)]]
- [[OSI Layer 4 (Transport)]]
- [[OSI Layer 5 (Session)]]
- [[OSI Layer 6 (Presentation)]]
- [[OSI Layer 7 (Application)]]
