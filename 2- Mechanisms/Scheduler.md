
The **scheduler** determines **which execution unit runs on the CPU and when**, coordinating how processing time is shared among concurrent workloads. It governs how work progresses across processes or threads over time.

---
### `How It Works`

Runnable execution units are placed into scheduling queues and selected based on defined criteria such as priority, fairness, or responsiveness.  

The scheduler periodically interrupts execution to reassess which unit should run next, switching CPU control as needed.

This selection process balances competing demands while respecting system policies and resource constraints.

---
### `Why It Exists`

- To enable **concurrent execution** of multiple workloads
- To ensure **fair and controlled CPU usage**
- To balance **responsiveness and throughput**
- To prevent starvation and maintain system stability

---
### `Connected Notes`

- [[Kernel Responsibilities]]