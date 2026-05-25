
### `Definition`

The **Shared Responsibility Model (SaaS)** explains how **security and operational responsibilities are divided** between the **cloud provider** and the **customer** when using **Software-as-a-Service**.

In SaaS, the provider manages **almost the entire stack**, while the customer focuses primarily on **data, access, and usage**.

---
### `Key Ideas`

- **Provider Manages the Full Stack**  
    The cloud provider is responsible for:
    
    - Physical data centers
    - Networking, servers, and storage
    - Operating systems
    - Runtime environments
    - Application code and updates
    - Platform availability and patching

- **Customer Focuses on Access and Data**  
    The customer is responsible for:
    
    - User access and identity management
    - Authentication methods (SSO, MFA)
    - Data classification and protection
    - Secure usage of the application
    - Compliance with organizational policies

- **Lowest Customer Control, Lowest Operational Burden**  
    Compared to IaaS and PaaS:
    
    - Minimal configuration control
    - No infrastructure or platform management
    - Fastest time to value

- **Misuse Is the Primary Risk**  
    Common SaaS risks include:
    
    - Weak passwords or missing MFA
    - Over-permissioned users
    - Data leakage through sharing features
    - Poor offboarding of users

- **Security Is Still Shared**  
    Even though the provider runs the application:
    
    - The provider secures the service
    - The customer secures how the service is accessed and used
    
    Responsibility is reduced — **never eliminated**.

---
### `Connected Notes`

- [[Shared Responsibility Model]]