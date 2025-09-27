## Cloud Infrastructure & Virtualization

### Cloud Data Centers & Architecture

- **Definition:** Cloud data centers are large-scale facilities that house physical servers, networking equipment, and storage resources. They are designed for redundancy, security, and scalability.
- **Key Features:** Cooling systems, backup power (UPS), disaster recovery, high-speed networking.
- **Example:** **AWS data centers** are spread across “Availability Zones” (AZs). If one AZ fails, traffic is automatically routed to another, ensuring zero downtime.

---

### Networking in the Cloud

- **Virtual Private Cloud (VPC):** Isolated cloud network for an organization.
- **Load Balancers:** Distribute traffic among multiple servers.
- **Firewalls & Security Groups:** Control inbound/outbound traffic.
- **Example:** When you visit **Airbnb**, your request is routed through AWS Elastic Load Balancer (ELB), which directs you to the nearest, healthiest server.

---

### Storage in the Cloud

- **Block Storage:** Like hard drives (e.g., AWS EBS). Best for databases.
- **File Storage:** Network-based file systems (e.g., Amazon EFS).
- **Object Storage:** Stores unstructured data (e.g., images, videos) with metadata (e.g., AWS S3).
- **Example:** **YouTube** stores videos in cloud object storage for fast global access.

---

### Virtualization Technologies

- **Hypervisors:** Software that creates and manages virtual machines.
  - _Examples:_ VMware ESXi, Microsoft Hyper-V, KVM.
- **How it works:** A physical server runs multiple virtual servers (VMs). Each VM can run its own OS.
- **Example:** A university runs both **Linux (for students)** and **Windows (for administration)** on the same hardware using VMware.

---

### Containers (Docker, Podman)

- **Definition:** Lightweight, portable units that package code, dependencies, and libraries.
- **Benefits:** Faster startup, less resource-heavy compared to VMs.
- **Example:** **Uber** uses containers to run microservices that handle ride matching, payments, and notifications separately.

---

### Container Orchestration (Kubernetes Basics)

- **Definition:** Tool for automating deployment, scaling, and management of containers.
- **Features:** Load balancing, self-healing, auto-scaling.
- **Example:** **Spotify** uses Kubernetes to manage thousands of containers running its music recommendation system.
