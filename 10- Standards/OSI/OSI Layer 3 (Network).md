
The **Network Layer (Layer 3)** of the **OSI Model** defines how data is **routed between different networks** using **logical addressing**.  
It establishes standards for **packet forwarding, routing, and path determination**, enabling communication beyond a single local network.

---
### `Purpose`

- Provides **end-to-end delivery** of packets across multiple interconnected networks.
    
- Uses **logical (IP) addressing** to uniquely identify devices globally.
    
- Determines **optimal paths** for data using routing algorithms.
    
- Handles **packet fragmentation and reassembly** when data exceeds transmission limits.
    
- Enables **internetworking** — connecting multiple LANs into a single global network (the Internet).

---
### `Structure`

|Aspect|Function|Examples|
|---|---|---|
|**Addressing**|Assigns logical IP addresses for routing.|IPv4, IPv6|
|**Routing**|Determines best path from source to destination.|OSPF, BGP, RIP|
|**Packet Forwarding**|Moves packets between networks using routers.|IP header routing|
|**Fragmentation**|Splits packets into smaller units for transmission.|IP fragmentation|
|**Devices**|Operate at Layer 3 to manage routing and forwarding.|Routers, Layer 3 switches|

**Data Unit:** _Packet_  
**Key Identifier:** _IP address (logical address)_

---
### `Connected Notes`

- [[OSI Model]]
- [[OSI Layer 2 (Data Link)]]
- [[OSI Layer 4 (Transport)]]
- [[IP Protocol Suite]]
- [[Routing and Switching]]
- [[Subnetting and IP Addressing]]