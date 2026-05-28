
**Phase 5 – Deployment** is the stage of the **Software Development Life Cycle (SDLC)** where the **tested application is released** to a live environment for **end users or customers**. It involves moving the software from staging or testing environments into **production**, ensuring that it operates as intended under real-world conditions.

---
### `Key Ideas`

- **Purpose:**  
    To **deliver the functional product** to users safely and efficiently while minimizing downtime and deployment risks.  
    This phase ensures the application is accessible, stable, and ready for real-world usage.
    
- **Inputs:**
    
    - Successfully tested build from the testing phase.
    - Deployment and rollback plan.
    - Configuration and environment details from technical documentation.
    
- **Core Activities:**
    
    - **Release Planning:**  
        Define the release strategy — **phased**, **big bang**, **blue/green**, or **canary deployment** — depending on the system’s complexity and risk level.
        
    - **Environment Configuration:**  
        Set up production servers, load balancers, cloud infrastructure, or CI/CD pipelines.  
        Validate environment consistency with staging and testing environments.
        
    - **Release Execution:**  
        Deploy code, run setup scripts, migrate databases, and configure integrations or APIs.
        
    - **Verification (Post-Deployment Testing):**  
        Conduct **smoke tests** or **UAT (User Acceptance Testing)** to ensure deployment success.  
        Monitor performance, logs, and error rates.
        
    - **Documentation & Communication:**  
        Update release notes, user guides, and notify stakeholders or users about new features, changes, or known issues.
    
- **Outputs:**
    
    - Fully operational production system.
    - Updated deployment and configuration documentation.
    - Initial performance and monitoring data.
    
- **Best Practices:**
    
    - Use automation (e.g., CI/CD, IaC) to reduce human error.
    - Maintain rollback plans for quick recovery from failed deployments.
    - Ensure version control and tagging for traceability.
    - Involve operations and QA teams to verify successful transition.
    - Monitor application health using observability and logging tools.

---
### `Connected Notes`

- [[SDLC Phases]]