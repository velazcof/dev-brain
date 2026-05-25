
### `Definition`

A Kubernetes Ingress is a mechanism responsible for **managing external access to services running inside a Kubernetes cluster**, typically for HTTP and HTTPS traffic. It provides centralized traffic routing rules that determine how incoming requests should reach internal services.

---
### `How It Works`

- **Traffic entry point**  
    Ingress acts as an entry layer between external clients and services inside the cluster, receiving incoming traffic and directing it appropriately.

- **Rule-based routing**  
    Routing behavior is defined through rules based on properties such as domain names, URL paths, or request patterns.

- **Service exposure abstraction**  
    Rather than exposing every service independently, Ingress provides a unified way to control how multiple services become externally accessible.

- **Ingress controller dependency**  
    Ingress itself only defines routing rules. An Ingress Controller implements those rules and performs the actual traffic handling.

---
### `Why It Exists`

- **Centralized traffic management**  
    Ingress simplifies external access by consolidating routing behavior into a single management layer.

- **Reduced infrastructure complexity**  
    Multiple services can share a common external entry point rather than requiring separate infrastructure exposure.

- **Web application scalability**  
    Ingress supports modern distributed applications by providing structured routing and traffic organization.

---
### `Connected Notes`

- [[Networking]]