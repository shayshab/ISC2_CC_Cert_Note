# ISC2 Certified in Cybersecurity (CC) - Detailed Point-Based Notes

## Domain 1: Security Principles

### 1. Confidentiality, Integrity, Availability, and Non-repudiation
- **Confidentiality** ensures that sensitive information is only accessible to authorized individuals. Techniques include encryption, access controls, and data classification. Threats include eavesdropping, social engineering, and unauthorized disclosure.
- **Integrity** protects information from unauthorized modification or destruction. This is achieved through hashing, digital signatures, and checksums. Threats include tampering, impersonation, and man-in-the-middle attacks.
- **Availability** guarantees that information and resources are accessible to authorized users when needed. Redundancy, backups, and disaster recovery plans help maintain availability. Threats include denial-of-service (DoS) attacks, hardware failures, and natural disasters.
- **Non-repudiation** provides proof of the origin and integrity of data, ensuring that a party cannot deny the authenticity of their signature or the sending of a message. Digital signatures and audit logs are common mechanisms.

### 2. Authentication and Authorization
- **Identification** is the process where a user claims an identity (e.g., entering a username).
- **Authentication** verifies the claimed identity, typically through passwords, biometrics, or tokens. Multi-factor authentication (MFA) combines two or more factors: something you know (password), something you have (token), and something you are (biometric).
- **Authorization** determines what actions or resources an authenticated user is allowed to access, often managed through roles or permissions.
- **Accounting (Auditing)** tracks user actions for accountability and forensic purposes, using logs and monitoring systems.
- **Password policies** should enforce minimum length, complexity (mix of character types), history (prevent reuse), and expiration. Users should avoid password reuse and use password managers.

### 3. Privacy
- IT professionals are responsible for protecting personal data, including Personally Identifiable Information (PII) and Protected Health Information (PHI). PII includes names, addresses, and identification numbers; PHI includes medical records and health data.
- The Privacy Management Framework (PMF) covers management, notice, collection, use, access, disclosure, security, data integrity, and monitoring. Organizations must provide clear privacy notices, limit data collection, ensure secure storage, and allow individuals to access and correct their data.

### 4. Risk Management
- **Risk** is the potential for loss or harm related to a threat exploiting a vulnerability. Risks can be internal (employee misconduct), external (cyberattacks), or multiparty (supply chain).
- **Threats** are external dangers; **vulnerabilities** are internal weaknesses. A risk exists when both are present.
- **Risk assessment** can be qualitative (subjective, e.g., high/medium/low) or quantitative (numeric, e.g., dollar value, probability).
- **Risk treatment** options: avoid (eliminate the risk), transfer (insurance, outsourcing), mitigate (reduce likelihood/impact), or accept (acknowledge and monitor).
- **Residual risk** is what remains after controls are applied.

### 5. Security Controls
- **Preventive controls** stop incidents before they occur (e.g., firewalls, access controls).
- **Detective controls** identify and alert on incidents (e.g., intrusion detection systems, monitoring).
- **Recovery controls** restore systems after an incident (e.g., backups, disaster recovery).
- Controls can be **technical** (encryption, authentication), **administrative** (policies, training), or **physical** (locks, guards).

### 6. Ethics
- The ISC2 Code of Ethics requires professionals to protect society, act honorably and legally, provide competent service, and advance the profession. Violations can result in disciplinary action.

### 7. Security Governance Processes
- Security governance includes policies (high-level rules), standards (specific requirements), guidelines (recommended practices), and procedures (step-by-step instructions).
- Compliance with laws and regulations (e.g., GDPR for privacy, PCI DSS for payment data) is mandatory. Organizations must be aware of all applicable legal requirements.

---

## Domain 2: Business Continuity, Disaster Recovery & Incident Response

### 8. Business Continuity
- **Business Impact Analysis (BIA)** identifies critical business functions and the IT systems that support them. It helps prioritize recovery efforts and resources.
- **High availability (HA)** uses redundant systems to minimize downtime. **Fault tolerance (FT)** ensures a single system can withstand failures (e.g., RAID for storage, dual power supplies).
- Common failure points include power supplies, storage devices, and network connections. Mitigation includes UPS, backup generators, RAID, and redundant network links.

### 9. Disaster Recovery
- **Recovery Time Objective (RTO)** is the maximum acceptable downtime after a disruption. **Recovery Point Objective (RPO)** is the maximum acceptable data loss, measured in time.
- **Backups**: Full (all data), differential (changes since last full), incremental (changes since last backup), mirror (real-time copy), cloud (off-site), local (on-site), hybrid (combination), and snapshot (point-in-time image).
- **Recovery sites**: Hot sites are fully equipped and ready for immediate use; warm sites have hardware/software but need setup; cold sites are basic facilities requiring significant setup.

### 10. Incident Response
- The NIST incident response process includes: preparation (planning, training, tools), detection & analysis (identifying and assessing incidents), containment (limiting damage), eradication & recovery (removing threats and restoring systems), and post-incident activity (lessons learned, reporting).
- Incident response teams include management, information security, physical security, legal, public relations, HR, and technical experts.
- The first priority is to contain the incident, followed by preserving evidence and restoring services. SIEM systems help with centralized log collection and analysis.

---

## Domain 3: Access Controls Concepts

### 11. Physical Access Controls
- Sensitive areas (data centers, server rooms, storage, wiring closets) require strong physical security: locks, surveillance, access logs, and environmental controls.
- Crime Prevention Through Environmental Design (CPTED) uses natural surveillance (lighting, sight lines), access control (fencing, landscaping), and territorial reinforcement (signs, barriers) to deter crime.
- Visitor access should be authorized, logged, and monitored. Two-person controls (integrity and concurrence) are used for highly sensitive areas or actions.

### 12. Logical Access Controls
- **Least privilege**: Users get only the permissions needed for their job.
- **Segregation of duties**: No single person has enough access to misuse a system alone.
- **Non-repudiation**: Users cannot deny actions, enforced by logs and digital signatures.
- **Access control models**:
  - DAC: Resource owners set permissions (flexible, less secure).
  - MAC: System enforces access based on labels (strict, used in government).
  - RBAC: Access based on roles (scalable, business-friendly).
  - ABAC: Access based on attributes (fine-grained, policy-driven).
  - Rule-based: Access based on system rules.
  - IBAC: Access based on user identity.
- **Subject-object-process**: A subject (user/process) requests to perform an action (process) on an object (resource).

---

## Domain 4: Network Security

### 13. Computer Networking
- The OSI model has 7 layers: Physical, Data Link, Network, Transport, Session, Presentation, Application. Each layer has specific functions (e.g., routing at Network, encryption at Presentation).
- TCP/IP is the main protocol suite. TCP is reliable and connection-oriented; UDP is faster and connectionless. IP provides addressing (IPv4: 32-bit, IPv6: 128-bit).
- Subnetting uses CIDR notation (e.g., /24 for 255.255.255.0). Common ports: 80 (HTTP), 443 (HTTPS), 22 (SSH), 25 (SMTP), 21 (FTP), 110 (POP3), 143 (IMAP), 53 (DNS), 3389 (RDP).
- Wi-Fi security uses WPA2/WPA3, enterprise authentication, and preshared keys.

### 14. Network Threats and Attacks
- **Malware** types: virus (needs user action), worm (self-spreading), trojan (disguised), ransomware (demands payment), spyware (monitors), adware (ads), rootkit (hides), keylogger (records keystrokes), botnet (network of infected devices), backdoor (unauthorized access).
- **Attacks**: Man-in-the-middle (intercepting communication), DoS/DDoS (overwhelming resources).

### 15. Threat Identification and Prevention
- **IDS/IPS**: Intrusion Detection/Prevention Systems can be host-based (HIDS/HIPS) or network-based (NIDS/NIPS). IDS detects and alerts; IPS can block threats.
- **Firewalls**: Control traffic based on rules. Types include packet filtering (simple), stateful (tracks connections), proxy (inspects content), NGFW (advanced features), WAF (web traffic), circuit-level, and hybrid.

### 16. Network Security Infrastructure
- Data centers require environmental controls (HVAC, fire suppression), physical security (locks, cameras), and logical controls.
- Network devices: switches (local connectivity), routers (routing between networks), firewalls (traffic filtering).
- Network zones: Internet (external), DMZ (public-facing), Intranet (internal).
- Network Access Control (NAC) checks device/user compliance before granting access.

### 17. Cloud Computing
- **Deployment models**: Public (shared), private (dedicated), community (shared by group), hybrid (mix).
- **Service models**: IaaS (infrastructure), PaaS (platform), SaaS (software), FaaS (function), CaaS (container), DBaaS (database).
- **Management**: Automation, orchestration, and infrastructure as code (IaC) streamline cloud operations.

---

## Domain 5: Security Operations

### 18. Encryption
- Encryption transforms readable data (plaintext) into unreadable ciphertext. Decryption reverses the process.
- **Data at rest** (stored) and **data in transit** (moving) should be encrypted to prevent unauthorized access.
- **Symmetric encryption** uses the same key for encryption/decryption (e.g., AES). **Asymmetric encryption** uses public/private key pairs (e.g., RSA). **Hashing** is one-way (e.g., SHA-256) for integrity. **Digital signatures** verify authenticity and integrity.

### 19. Data Handling
- Data lifecycle: creation, storage, use, sharing, archiving, destruction. Each stage requires appropriate security controls.
- Data classification: Top Secret, Secret, Confidential, Unclassified (military); Highly Sensitive, Sensitive, Internal, Public (business). Classification determines handling and access requirements.
- Data labeling and handling must be standardized to prevent leaks and ensure compliance.

### 20. Logging and Monitoring
- Logs provide accountability (who did what), traceability (event correlation), and auditability (compliance evidence).
- SIEM systems centralize log collection, ensure integrity, and use correlation/AI to detect threats.

### 21. Configuration Management
- Configuration management documents and controls changes to systems, reducing errors and unauthorized changes.
- Baselines are reference configurations; deviations may indicate security issues.
- Regular patching and updates address vulnerabilities and maintain security.

### 22. Best Practice Security Policies
- Security policies include acceptable use, data handling, password, BYOD, privacy, and change management. They set expectations and requirements for users and IT staff.

### 23. Security Awareness Training
- Social engineering tactics exploit authority, trust, intimidation, consensus, scarcity, and familiarity. Training helps users recognize and resist these tactics.
- Effective training is ongoing, engaging, and tailored to roles. It should include incident reporting procedures and regular testing.

---

*Use these detailed notes for in-depth study and understanding. For quick review, refer to the concise or table-based versions.* 