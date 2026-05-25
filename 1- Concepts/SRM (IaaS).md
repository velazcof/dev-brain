
### `Definition`

The **Shared Responsibility Model (IaaS)** defines how **security and operational responsibilities are split** between the **cloud provider** and the **customer** when using **Infrastructure-as-a-Service**.

In IaaS, the provider supplies the **infrastructure**, while the customer retains significant control—and responsibility—over the **operating system and everything above it**.

---
### `Key Ideas`

- **Provider Manages the Physical Infrastructure**  
    The cloud provider is responsible for:
    
    - Physical data centers
    - Networking hardware
    - Servers and storage
    - Physical security
    - Availability of the infrastructure

- **Customer Manages the OS and Above**  
    The customer is responsible for:
    
    - Operating system installation, configuration, and patching
    - System hardening
    - Network configuration (security groups, firewalls, routing)
    - Applications and application code
    - Data and data protection
    - Identity and access management

- **Highest Customer Responsibility Among Cloud Models**  
    Compared to PaaS and SaaS:
    
    - More flexibility
    - More control
    - More risk if misconfigured

- **Misconfiguration Is the Primary Risk**  
    Most IaaS breaches stem from:
    
    - Exposed ports
    - Weak firewall rules
    - Unpatched OS vulnerabilities
    - Poor access controls

- **Security Is Still Shared**  
    The provider secures the infrastructure **of** the cloud,  
    while the customer secures what runs **in** the cloud.

---
### `Connected Notes`

- [[Shared Responsibility Model]]