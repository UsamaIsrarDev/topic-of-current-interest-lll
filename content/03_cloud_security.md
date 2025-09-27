## Cloud Security & Compliance

### Importance of Cloud Security

- Cloud platforms host **sensitive data** (personal info, banking, healthcare).
- Without security, risks include **data breaches, financial loss, and reputational damage**.
- **Example:** In 2019, **Capital One** suffered a massive data breach due to a misconfigured firewall in AWS.

---

### Cloud Security Threats

- **Data Breaches** – Unauthorized access (e.g., hackers stealing customer info).
- **DDoS Attacks** – Flooding servers to make apps unavailable.
- **Insider Threats** – Employees leaking or misusing data.
- **Example:** **GitHub** faced a record-breaking DDoS attack in 2018, which was mitigated by cloud-based protection.

---

### Shared Responsibility Model

- **Cloud Provider (AWS, Azure, GCP):** Secures infrastructure (data centers, hardware, networking).
- **Customer (You/Company):** Secures applications, data, identity access.
- **Example:** In AWS, **you must configure IAM policies** correctly; AWS won’t do it for you.

---

### Identity & Access Management (IAM)

- **Definition:** Controlling “who can access what.”
- **Features:** Multi-factor authentication (MFA), Role-based access control (RBAC).
- **Example:** A company gives **read-only access** to interns but **admin access** to system engineers.

---

### Encryption & Data Protection

- **At Rest:** Data stored securely in disks/databases (e.g., AES-256).
- **In Transit:** Data encrypted while moving (e.g., TLS/SSL).
- **Example:** **WhatsApp** uses end-to-end encryption to protect messages.

---

### Compliance & Regulations

- **GDPR (Europe):** Protects user privacy and data rights.
- **HIPAA (USA):** Ensures patient data confidentiality in healthcare.
- **PCI-DSS:** For companies handling credit card transactions.
- **Example:** **PayPal** must follow PCI-DSS to process your online payments securely.
