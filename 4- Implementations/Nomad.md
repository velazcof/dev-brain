
Nomad is a **workload orchestration platform developed by HashiCorp** that schedules and manages applications across clusters of machines.

It can orchestrate multiple types of workloads, including **containers, virtual machines, and standalone applications**, providing a flexible alternative to container-specific orchestrators.

---
### `Key Capabilities`

- Schedules workloads across **distributed clusters**
    
- Supports multiple workload types including **containers, VMs, and binaries**
    
- Provides **automatic scaling and workload placement**
    
- Enables **high availability and failover**
    
- Integrates with the **HashiCorp ecosystem** for service discovery and security
    
- Uses **declarative job specifications** to define workloads
    
- Designed to be **lightweight and operationally simple**

---
### `Usage Basics`

**Basic workflow:**

1. Define a workload using a **Nomad job specification**
    
2. Submit the job to a Nomad cluster
    
3. Nomad schedules the workload on available nodes
    
4. The platform manages execution, scaling, and recovery

**Example job specification:**

```hcl
job "example" {  
  datacenters = ["dc1"]  
  
  group "web" {  
    task "nginx" {  
      driver = "docker"  
  
      config {  
        image = "nginx"  
        ports = ["http"]  
      }  
  
      resources {  
        cpu    = 500  
        memory = 256  
      }  
    }  
  }  
}
```

**Run the job:**

```bash
nomad run example.nomad
```

---
### `Challenges`

- Smaller ecosystem compared to Kubernetes
    
- Fewer community tools and integrations
    
- Less adoption in large enterprise environments
    
- Requires additional tools for features like service discovery
    
- Limited visibility in mainstream container orchestration discussions

---
### `Connected Notes`

- [[Container Orchestrators]]