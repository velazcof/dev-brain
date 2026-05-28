
The **Physical Layer (Layer 1)** of the **OSI Model** defines the **electrical, mechanical, and procedural standards** for transmitting raw bits across a physical medium.  It establishes how **0s and 1s** are represented, transmitted, and received between devices over cables, fiber optics, or wireless signals.

---
### `Purpose`

- Ensures **reliable physical transmission** of data between connected devices.
    
- Defines how hardware components (NICs, cables, connectors, hubs) operate and interact.
    
- Converts digital data into **electrical, optical, or radio signals** suitable for the chosen medium.
    
- Provides the **foundation** for all higher OSI layers — without it, no communication is possible.

---
### `Structure`

|Aspect|Description|Examples|
|---|---|---|
|**Signals**|Defines voltage levels, modulation, and bit encoding.|NRZ, Manchester encoding|
|**Mediums**|Specifies the physical transmission media.|Ethernet cables, fiber optics, Wi-Fi, Bluetooth|
|**Connectors**|Mechanical interfaces that connect hardware.|RJ45, LC, USB-C|
|**Devices**|Operate purely at the physical level.|Hubs, repeaters, cables|
|**Data Unit**|Transmits raw **bits (0s and 1s)** with no structure.|Binary signals|

Errors at this layer usually involve **hardware faults**, **signal interference**, or **improper cabling**.

---
### `Connected Notes`

- [[OSI Model]]
- [[OSI Layer 2 (Data Link)]]
- [[Network Cabling and Media Types]]
- [[Signal Encoding and Modulation]]