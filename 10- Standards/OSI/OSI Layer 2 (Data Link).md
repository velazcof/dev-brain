
The **Data Link Layer (Layer 2)** of the **OSI Model** defines how data is **packaged into frames** and transmitted across a **local network segment**.  It establishes standards for **MAC addressing, error detection, and reliable frame delivery** between directly connected devices.

---
### `Purpose`

- Provides **node-to-node communication** within the same local network (LAN).
    
- Ensures **error detection and correction** for data received from the Physical layer.
    
- Uses **MAC addresses** to identify devices uniquely on the network.
    
- Enables **medium access control**, preventing data collisions on shared channels.
    
- Bridges the gap between **physical signals (Layer 1)** and **logical addressing (Layer 3)**.

---
### `Structure`

|Sub-Layer|Function|Examples|
|---|---|---|
|**Logical Link Control (LLC)**|Interfaces with the Network layer and manages frame synchronization and error checking.|IEEE 802.2|
|**Media Access Control (MAC)**|Controls access to the physical medium and defines addressing rules.|Ethernet (802.3), Wi-Fi (802.11)|

**Data Unit:** _Frame_ — includes headers (MAC source/destination), payload, and checksum (CRC).  
**Devices:** Switches, network interface cards (NICs), bridges.

---
### `Connected Notes`

- [[OSI Model]]
- [[OSI Layer 1 (Physical)]]
- [[OSI Layer 3 (Network)]]
- [[Ethernet Standards]]
- [[MAC Addressing]]