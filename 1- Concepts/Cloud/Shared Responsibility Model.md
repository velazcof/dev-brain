
The **Shared Responsibility Model (SRM)** is a conceptual framework that defines **how responsibility for security and operations is divided** between a **cloud service provider (CSP)** and the **customer**.

It explains **who is responsible for what** when using cloud services.

---
### `Key Ideas`

- **Responsibility Is Split, Not Transferred**  
    Moving to the cloud does **not** mean security is fully handled by the provider.  
    Responsibility is **shared** across defined boundaries.
    
- **Provider vs Customer Roles**
    
    - **Cloud Provider** → Security **of** the cloud  
        Physical data centers, hardware, underlying infrastructure, and core platform services.
        
    - **Customer** → Security **in** the cloud  
        Configuration, data protection, identity management, network rules, and application security.
    
- **Varies by Service Model**
    
    - **IaaS** → Customer manages OS, network config, apps, data
    - **PaaS** → Customer manages apps and data
    - **SaaS** → Customer mainly manages data and access
    
- **Always Applies**  
    The model applies regardless of:
    
    - Cloud provider (AWS, Azure, GCP)
    - Tooling choices
    - Security maturity
    
- **Misunderstanding Is a Common Failure Point**  
    Many cloud security incidents happen because customers assume the provider covers responsibilities that actually belong to them.

---
### `Connected Notes`

- [[Cloud Security]]
- [[SRM (IaaS)]]
- [[SRM (PaaS)]]
- [[SRM (SaaS)]]