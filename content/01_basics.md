## 🔹 Module 1: Introduction to Cloud Computing (Basics)

### **1. What is Cloud Computing?**

**Definition:**
Cloud computing is the delivery of computing resources—such as servers, storage, databases, networking, software, and analytics—over the internet (“the cloud”) on a pay-as-you-go basis.

**Real-World Example:**
Instead of buying expensive servers, Netflix uses **AWS Cloud** to stream movies to millions of users worldwide. When traffic spikes (like during the release of a new series), Netflix instantly scales up cloud servers.

---

### **2. Characteristics of Cloud Computing**

1. **On-demand self-service** – You can rent resources anytime without human interaction.

   - _Example:_ Developers create new virtual machines in **AWS EC2** in seconds.

2. **Scalability & Elasticity** – Resources can scale up/down based on demand.

   - _Example:_ E-commerce sites like **Daraz** or **Amazon** handle Black Friday traffic spikes by auto-scaling servers.

3. **Measured Service (Pay-as-you-go)** – You pay only for what you use.

   - _Example:_ Google Drive charges for storage used beyond free limits.

4. **Resource Pooling** – Multiple customers share the same physical resources securely.

   - _Example:_ Microsoft Azure hosts many companies’ apps on shared servers using virtualization.

5. **Broad Network Access** – Access from anywhere, anytime, on any device.

   - _Example:_ Gmail is accessible via laptops, mobiles, tablets—all cloud-powered.

---

### **3. Cloud Deployment Models**

1. **Public Cloud**

   - Resources owned and managed by third-party providers (AWS, Azure, GCP).
   - _Example:_ A startup using AWS EC2 for hosting their website without buying hardware.

2. **Private Cloud**

   - Dedicated cloud infrastructure used by a single organization.
   - _Example:_ A bank builds its **own private cloud** to store sensitive financial data securely.

3. **Hybrid Cloud**

   - Combination of public + private cloud for flexibility.
   - _Example:_ A hospital keeps patient data in a private cloud (secure) but uses AWS AI services for disease prediction.

4. **Multi-Cloud**

   - Using services from multiple cloud providers simultaneously.
   - _Example:_ Spotify uses **Google Cloud** for analytics and **AWS** for hosting.

---

### **4. Cloud Service Models**

1. **IaaS (Infrastructure as a Service)**

   - Provides virtualized computing resources (servers, storage, networking).
   - _Example:_ A gaming company rents **AWS EC2** servers to run multiplayer online games.

2. **PaaS (Platform as a Service)**

   - Provides a platform for developers to build, test, and deploy apps without managing servers.
   - _Example:_ A developer uses **Heroku** or **Google App Engine** to deploy an app quickly.

3. **SaaS (Software as a Service)**

   - Software hosted in the cloud, accessible via browsers.
   - _Example:_ **Google Workspace (Docs, Sheets, Drive)** and **Microsoft Office 365** are SaaS.

4. **FaaS (Function as a Service)** (aka Serverless Computing)

   - Run code in response to events without managing servers.
   - _Example:_ When you upload a picture to **Instagram**, a serverless function (like AWS Lambda) automatically compresses and saves it.

---

### **5. Virtualization Basics (VMs vs Containers)**

1. **Virtual Machines (VMs)**

   - Full OS + virtualized hardware (like multiple PCs on one server).
   - _Example:_ A company runs Windows Server and Linux Server as VMs on the same machine using **VMware**.

2. **Containers**

   - Lightweight, share the host OS kernel, faster than VMs.
   - _Example:_ **Docker containers** run multiple microservices (like authentication, payments, notifications) separately in an e-commerce app.

**Real Difference Example:**

- If you run **Netflix**, each microservice (recommendation engine, video player, billing) may run inside a container.
- But if you want to test a **Windows-only legacy app**, you’d use a VM.

---
