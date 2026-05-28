
Direct-Attached Storage (DAS) refers to physical storage devices that are directly connected to a single computer or server — without going through a network.

It’s the simplest and fastest way to access data locally, as the compute node communicates directly with the storage hardware.

---
### `Key Ideas`

- **Architecture:** The storage (like HDDs or SSDs) connects to the host system via interfaces such as SATA, NVMe, or SAS.
    
- **Access Model:** Only the attached system can directly access the data — unlike NAS (Network-Attached Storage) or SAN (Storage Area Network), which serve multiple systems over a network.
    
- **Performance:** Offers very low latency and high throughput because there’s no network overhead.
    
- **Scalability:** Limited — adding capacity usually means physically installing more drives on the same machine.
    
- **Management:** Simple setup and minimal configuration, but lacks centralized management and data sharing between multiple servers.

---
### `Use Cases`

- **Single-server applications:** Ideal when one machine handles all compute and storage needs (e.g., local databases, logging servers).
    
- **High-performance workloads:** Useful for workloads needing fast, direct disk access (e.g., caching, gaming servers, edge computing).
    
- **Development and testing:** Common in local or lab environments for simplicity and speed.
    
- **Backup or secondary storage:** Can serve as quick local backup before pushing data to network or cloud storage.

---
### `Connected Notes`

- [[Storage Variants]]