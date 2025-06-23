# ISC2 Certified in Cybersecurity (CC) - Concise Point-Based Notes

## Domain 1: Security Principles

### 1. Confidentiality, Integrity, Availability, and Non-repudiation
- The CIA triad consists of Confidentiality (protecting information from unauthorized access), Integrity (preventing unauthorized modification), and Availability (ensuring information is accessible when needed).
- Non-repudiation ensures that actions cannot be denied by the user who performed them, often using digital signatures and audit logs.

### 2. Authentication and Authorization
- Access control involves identification, authentication, authorization, and accounting.
- Multi-factor authentication uses two or more of: something you know, have, or are.
- Password policies should enforce length, complexity, history, and expiration.

### 3. Privacy
- IT professionals must protect personal information, including PII and PHI.
- The Privacy Management Framework (PMF) includes principles like management, notice, collection, use, access, disclosure, security, integrity, and monitoring.

### 4. Risk Management
- Risks can be internal, external, or multiparty.
- Threats exploit vulnerabilities, creating risk.
- Risk is assessed qualitatively (subjective) or quantitatively (numeric).
- Risk treatment: avoid, transfer, mitigate, or accept.

### 5. Security Controls
- Controls are preventive (stop issues), detective (identify issues), or recovery (restore after issues).
- Mechanisms: technical (technology), administrative (process), or physical (real-world barriers).

### 6. Ethics
- ISC2 Code of Ethics: protect society, act honorably, provide competent service, and advance the profession.

### 7. Security Governance Processes
- Security documents: policies, standards, guidelines, and procedures.
- Compliance with laws (e.g., GDPR, PCI DSS) is mandatory.

---

## Domain 2: Business Continuity, Disaster Recovery & Incident Response

### 8. Business Continuity
- Business Impact Analysis (BIA) identifies critical functions and supporting systems.
- High availability and fault tolerance reduce downtime.
- Common failure points: power, storage, network.

### 9. Disaster Recovery
- RTO: maximum acceptable downtime. RPO: maximum acceptable data loss.
- Backups: full (all data), differential (since last full), incremental (since last backup), mirror, cloud, local, hybrid, snapshot.
- Recovery sites: hot (ready now), warm (partially ready), cold (infrastructure only).

### 10. Incident Response
- NIST process: preparation, detection & analysis, containment, eradication & recovery, post-incident activity.
- Teams include management, security, legal, PR, HR, and technical experts.
- First priority: contain damage; then preserve evidence and restore services.

---

## Domain 3: Access Controls Concepts

### 11. Physical Access Controls
- Secure sensitive areas: data centers, server rooms, storage, wiring closets.
- Use CPTED: surveillance, access control, territorial reinforcement.
- Visitor access must be logged and controlled; use two-person controls for sensitive areas.

### 12. Logical Access Controls
- Principles: least privilege, segregation of duties, non-repudiation.
- Models: DAC (owner controls), MAC (system enforces), RBAC (role-based), ABAC (attribute-based), Rule-based, IBAC (identity-based).
- Subject-object-process: user/process requests access to a resource.

---

## Domain 4: Network Security

### 13. Computer Networking
- OSI model: 7 layers from Physical to Application.
- TCP/IP: IP for routing, TCP (reliable), UDP (fast, connectionless).
- IPv4 (32-bit), IPv6 (128-bit). Subnetting uses CIDR notation (e.g., /24).
- Common ports: 80 (HTTP), 443 (HTTPS), 22 (SSH), 25 (SMTP), 21 (FTP), 110 (POP3), 143 (IMAP), 53 (DNS), 3389 (RDP).

### 14. Network Threats and Attacks
- Malware: virus, worm, trojan, ransomware, spyware, adware, rootkit, keylogger, botnet, backdoor.
- Attacks: man-in-the-middle, DoS, DDoS.

### 15. Threat Identification and Prevention
- IDS/IPS: host-based (HIDS/HIPS) and network-based (NIDS/NIPS).
- Firewalls filter traffic; types include packet filtering, stateful, proxy, NGFW, WAF, circuit-level, hybrid.

### 16. Network Security Infrastructure
- Data centers need environmental, fire, and physical controls.
- Devices: switches, routers, firewalls.
- Zones: Internet (low trust), DMZ (public), Intranet (internal).
- NAC verifies device and user compliance before network access.

### 17. Cloud Computing
- Deployment: public, private, community, hybrid.
- Services: IaaS (infrastructure), PaaS (platform), SaaS (software), FaaS (function), CaaS (container), DBaaS (database).
- Management: automation, orchestration, infrastructure as code.

---

## Domain 5: Security Operations

### 18. Encryption
- Encryption transforms plaintext to ciphertext; decryption reverses it.
- Data at rest (stored) and data in transit (moving) should be encrypted.
- Symmetric (same key), asymmetric (public/private keys), hashing (one-way), digital signatures (authenticity).

### 19. Data Handling
- Data lifecycle: creation, storage, use, sharing, archiving, destruction.
- Classification: Top Secret, Secret, Confidential, Unclassified (military); Highly Sensitive, Sensitive, Internal, Public (business).
- Labeling and handling must be standardized.

### 20. Logging and Monitoring
- Logs provide accountability, traceability, and auditability.
- SIEM systems centralize, correlate, and analyze logs.

### 21. Configuration Management
- Document and control changes to systems.
- Use baselines to detect unauthorized changes.
- Patch and update systems to fix vulnerabilities.

### 22. Best Practice Security Policies
- Policies: acceptable use, data handling, password, BYOD, privacy, change management.

### 23. Security Awareness Training
- Social engineering tactics: authority, trust, intimidation, consensus, scarcity, familiarity.
- Training should be continuous, engaging, and role-specific.

---

*Use these concise notes for quick review and last-minute exam preparation. For details and comparisons, refer to the table-based version.* 