
### `Definition`

A **Content Delivery Network (CDN)** is a **distributed system of servers (edge nodes)** positioned across different geographic regions to deliver digital content—such as images, videos, scripts, and APIs—quickly and reliably to users.

It works as a **middle layer** between the client and the origin server, caching and routing content closer to users to minimize latency and bandwidth usage.

---
### `Key Ideas`

- **Distributed Caching:**  
    CDNs replicate static or semi-static content across global **Points of Presence (PoPs)**, so users download assets from the nearest edge instead of the distant origin server.
    
- **Smart Routing:**  
    Uses **DNS-based redirection** or **Anycast routing** to send users to the most optimal PoP based on proximity, congestion, or health.
    
- **HTTP Integration:**  
    Operates at the **application layer** using HTTP and HTTPS. Relies on caching headers (`Cache-Control`, `ETag`, `Expires`) to manage freshness and invalidation.
    
- **Security Layer:**  
    Provides **TLS termination**, **DDoS protection**, **bot filtering**, and **WAF (Web Application Firewall)** capabilities at the edge.
    
- **Dynamic Optimization:**  
    Can compress, resize, or transform content (e.g., image optimization, Brotli compression) before serving to clients.
    
- **Architecture Overview:**
    `User → Nearest Edge (CDN PoP) → (Cache Miss) → Origin Server`
    
- **Nature:**  
    A **technology / system architecture**, not a formal standard — it’s built on web protocols like **HTTP, DNS, and TLS**.

---
### `Use Cases`

- **Website Acceleration:** Reduce page load time by serving assets from local PoPs.
- **Global Content Distribution:** Deliver static and streaming content efficiently worldwide.
- **API & Edge Caching:** Improve latency and scalability for API-driven applications.
- **DDoS Mitigation:** Absorb or deflect large volumes of malicious traffic.
- **SSL/TLS Offloading:** Terminate secure connections at the edge to reduce origin load.
- **Video & Game Distribution:** Handle large downloads or live video streams to millions of users.

---
### `Connected Notes`

- [[Cloud Network]]