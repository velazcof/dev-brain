
API Gateways are software technologies that **serve as centralized entry points for APIs and backend services**, managing how client requests are received, processed, and routed.

They abstract underlying services behind a unified interface, simplifying access and enforcing cross-cutting concerns such as security and traffic management.

---
### `Key Ideas`

- **Unified API access**  
    API gateways provide a single endpoint through which clients can interact with multiple backend services or APIs.
- **Request processing**  
    They can perform operations such as authentication, authorization, rate limiting, request transformation, and protocol translation before forwarding requests.
- **Traffic management**  
    API gateways route requests to appropriate backend services and can enforce policies to improve reliability and scalability.
- **Microservices integration**  
    In distributed architectures, API gateways help reduce client complexity by hiding internal service boundaries and implementation details.

---
### `Use Cases`

- Exposing APIs to external consumers
- Managing authentication and authorization
- Enforcing rate limits and quotas
- Aggregating multiple backend services
- Simplifying access to microservices architectures
- Monitoring and logging API traffic

---
### `Connected Notes`

- [[Web Infrastructure]]
- [[Kong]]
- [[Apigee]]
- [[KrakenD]]