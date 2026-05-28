
The **Shared Responsibility Model (PaaS)** describes how **security and operational responsibilities are divided** between the **cloud provider** and the **customer** when using a **Platform-as-a-Service** offering.

In PaaS, the provider manages the **infrastructure and runtime platform**, while the customer focuses on **application logic and data**.

---
### `Key Ideas`

- **Provider Manages the Platform**  
    The cloud provider is responsible for:
    
    - Physical data centers
    - Networking
    - Servers and storage
    - Operating system
    - Runtime environment (language runtimes, middleware)
    - Platform patching and availability

- **Customer Manages the Application**  
    The customer is responsible for:
    
    - Application code
    - Application configuration
    - Data and data protection
    - Identity and access within the application
    - Secure use of platform services

- **Less Responsibility Than IaaS**  
    Compared to IaaS:
    
    - No OS management
    - No runtime patching
    - No infrastructure hardening  
        This reduces operational burden but also reduces control.

- **Security Is Still Shared**  
    Even though the platform is managed:
    
    - Insecure code can still cause breaches
    - Misconfigured services can expose data
    - Poor identity management remains a customer risk

- **Abstraction Increases Responsibility Shift**  
    As abstraction increases (IaaS → PaaS → SaaS), more responsibility moves to the provider — but **never fully disappears**.

---
### `Connected Notes`

- [[Shared Responsibility Model]]