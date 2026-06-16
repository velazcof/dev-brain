
Load Balancers are software technologies that **distribute incoming traffic across multiple backend servers or services** to improve scalability, availability, and reliability.

They act as a traffic distribution layer, preventing any single server from becoming overwhelmed while ensuring requests are routed to healthy instances.

---
### `Key Ideas`

- **Traffic distribution**  
    Load balancers spread requests across multiple backend instances using algorithms such as round-robin, least connections, or weighted routing.
- **High availability**  
    By directing traffic away from failed or unhealthy instances, load balancers help maintain service availability and fault tolerance.
- **Scalability support**  
    Applications can scale horizontally by adding more backend instances without changing how clients access the service.
- **Infrastructure abstraction**  
    Clients communicate with a single endpoint while the load balancer manages the complexity of backend service selection and routing.

---
### `Use Cases`

- Distributing traffic across web servers
- Scaling microservices and APIs
- Improving application reliability
- Performing health checks on backend services
- Managing traffic in cloud and Kubernetes environments

---

### `Connected Notes`

- [[Web Infrastructure]]
- [[NGINX]]
- [[HAProxy]]
- [[Envoy]]
- [[F5 BIG-IP]]