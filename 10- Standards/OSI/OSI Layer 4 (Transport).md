
The **Transport Layer (Layer 4)** of the **OSI Model** defines how data is **reliably delivered** between end systems.  
It establishes standards for **segmentation, flow control, error recovery, and session multiplexing**, ensuring complete data transfer between applications.

---
### `Purpose`

- Provides **end-to-end communication** between devices, abstracting lower network complexities.
    
- Ensures **reliable or best-effort delivery** depending on the protocol used (e.g., TCP vs. UDP).
    
- Manages **segmentation and reassembly** of data into smaller units for transmission.
    
- Handles **flow control** and **error checking** to prevent data loss or duplication.
    
- Enables **multiplexing**, allowing multiple applications to share the same network connection through **port numbers**.

---
### `Structure`

|Aspect|Function|Examples|
|---|---|---|
|**Segmentation / Reassembly**|Breaks data into segments for transmission and reassembles at destination.|TCP segmentation|
|**Reliability**|Acknowledgments, retransmission, sequencing.|TCP|
|**Flow Control**|Prevents overwhelming the receiver with too much data.|TCP sliding window|
|**Multiplexing**|Identifies multiple sessions using ports.|TCP/UDP ports|
|**Connection Type**|Defines connection-oriented vs. connectionless transport.|TCP (reliable), UDP (unreliable)|

**Data Unit:** _Segment (TCP)_ or _Datagram (UDP)_  
**Devices:** Firewalls, load balancers, transport gateways.

---
### `Connected Notes`

- [[OSI Model]]
- [[OSI Layer 3 (Network)]]
- [[OSI Layer 5 (Session)]]
- [[TCP Protocol]]
- [[UDP Protocol]]
- [[Port Numbers and Sockets]]