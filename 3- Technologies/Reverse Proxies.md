
Reverse Proxies are software technologies that **act on behalf of servers, receiving client requests and forwarding them to backend services or applications**. They sit between clients and server infrastructure, abstracting and managing access to backend systems.

---
### `Key Ideas`

- **Server-side intermediary**  
    Reverse proxies represent backend services rather than clients. Clients interact with the proxy, which routes requests to the appropriate servers.
- **Traffic routing and distribution**  
    Reverse proxies can direct requests to different services based on criteria such as domain names, URL paths, or application rules.
- **Security and abstraction**  
    By hiding backend infrastructure from external clients, reverse proxies improve security and decouple clients from internal system details.
- **Performance optimization**  
    Reverse proxies often provide capabilities such as caching, SSL/TLS termination, compression, and load balancing to improve scalability and efficiency.

---
### `Use Cases`

- Exposing applications to external users
- Routing traffic in microservices architectures
- Performing SSL/TLS termination
- Caching frequently requested content
- Load balancing across multiple backend servers
- Acting as ingress points for Kubernetes clusters

---
### `Connected Notes`

- [[Proxies]]
- [[NGINX]]
- [[HAProxy]]
- [[Traefik]]
- [[Envoy]]