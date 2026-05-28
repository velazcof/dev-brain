
The **Presentation Layer (Layer 6)** of the **OSI Model** defines how data is **translated, formatted, encrypted, and compressed** for application use. It acts as the **translator** between network data and application data, ensuring that information sent by one system can be understood by another.

---
### `Purpose`

- Provides a **common data representation** across different systems and architectures.
    
- Handles **data conversion** between application formats (e.g., text, binary, images).
    
- Manages **encryption and decryption** to secure transmitted data.
    
- Performs **compression and decompression** to improve transmission efficiency.
    
- Ensures **syntax and semantics** of exchanged data are preserved across platforms.

---
### `Structure`

|Aspect|Function|Examples|
|---|---|---|
|**Data Translation**|Converts between different encoding formats.|ASCII ↔ EBCDIC, JSON ↔ XML|
|**Encryption / Decryption**|Secures data before transmission.|SSL/TLS, AES|
|**Compression / Decompression**|Reduces data size for faster transmission.|MPEG, JPEG, ZIP|
|**Serialization**|Structures complex data for network transfer.|ASN.1, Protocol Buffers|

**Data Unit:** _Data_ (formatted for the application layer)  
**Devices / Components:** Gateways, encryption modules, codecs.

---
### `Connected Notes`

- [[OSI Model]]
- [[OSI Layer 5 (Session)]]
- [[OSI Layer 7 (Application)]]
- [[Data Encryption and SSL/TLS]]
- [[Data Encoding and Serialization]]
- [[Compression Algorithms]]