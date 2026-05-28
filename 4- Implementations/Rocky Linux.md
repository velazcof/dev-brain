
**Rocky Linux** is a **free, community-driven, enterprise-grade Linux distribution** that is **binary-compatible with Red Hat Enterprise Linux (RHEL)**.

It was created to provide a **drop-in replacement for CentOS Linux** after its shift to CentOS Stream, targeting **production servers, enterprise workloads, and long-term stability** without licensing costs.

---
### `Key Capabilities`

- **RHEL Binary Compatibility**  
    Designed to be **1:1 compatible** with RHEL, allowing:
    
    - Seamless migration from CentOS or RHEL
    - Compatibility with RHEL-targeted software and tooling
    
- **Long-Term Stability & Support**  
    Follows RHEL’s release lifecycle, offering:
    
    - Long support windows per major version
    - Security patches and bug fixes aligned with RHEL
    
- **RPM & DNF Ecosystem**  
    Uses:
    
    - `.rpm` packages
    - **DNF** as the package manager  
        Fully compatible with the RHEL/CentOS ecosystem.
    
- **Enterprise-Ready Security**
    
    - SELinux enabled by default
    - Regular security updates
    - Suitable for regulated or production environments
    
- **Cloud & Virtualization Friendly**  
    Official images available for:
    
    - AWS, Azure, GCP
    - VMware, KVM, VirtualBox
    
- **Community Governance**  
    Maintained by the **Rocky Enterprise Software Foundation (RESF)**, ensuring:
    
    - Vendor neutrality
    - Community-first development
    - Long-term project sustainability

---
### `Use Cases`

- Replacement for CentOS Linux in production
- Enterprise servers without RHEL subscription costs
- Cloud infrastructure and virtual machines
- Kubernetes worker nodes and container hosts
- On-premise data centers requiring stability and predictability

---
### `Challenges`

- **No Commercial Support by Default**  
    Relies on community support (third-party enterprise support exists).
    
- **Slight Lag Behind RHEL**  
    Updates may trail RHEL releases briefly due to rebuild process.
    
- **Not a Rolling Release**  
    Prioritizes stability over cutting-edge packages.

---
### `Connected Notes`

- [[RPM-based Distributions]]