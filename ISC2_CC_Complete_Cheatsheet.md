# ISC2 Certified in Cybersecurity (CC) Complete Exam Cheatsheet

## Table of Contents
1. [Domain 1: Security Principles](#domain-1-security-principles)
2. [Domain 2: Business Continuity, Disaster Recovery & Incident Response](#domain-2-business-continuity-disaster-recovery--incident-response)
3. [Domain 3: Access Controls Concepts](#domain-3-access-controls-concepts)
4. [Domain 4: Network Security](#domain-4-network-security)
5. [Domain 5: Security Operations](#domain-5-security-operations)
6. [Quick Reference Tables](#quick-reference-tables)

---

## Domain 1: Security Principles

### Chapter 1: Confidentiality, Integrity, Availability, and Non-repudiation

#### CIA Triad Summary
| Component | Goal | Threats | Controls |
|-----------|------|---------|----------|
| **Confidentiality** | Prevent unauthorized access | • Snooping<br>• Dumpster diving<br>• Eavesdropping<br>• Wiretapping<br>• Social engineering | • Encryption<br>• Access controls<br>• Data classification |
| **Integrity** | Prevent unauthorized modification | • Unauthorized modification<br>• Impersonation attacks<br>• Man-in-the-middle attacks<br>• Replay attacks | • Digital signatures<br>• Checksums<br>• Hash functions |
| **Availability** | Ensure access when needed | • Denial-of-service attacks<br>• Power outages<br>• Hardware failures<br>• Destruction of equipment<br>• Service outages | • Redundancy<br>• Backups<br>• Fault tolerance |

#### Non-repudiation Controls
| Control | Description | Implementation |
|---------|-------------|----------------|
| **Digital Signatures** | Mathematical verification of authenticity | RSA, DSA algorithms |
| **Audit Logs** | Comprehensive activity records | SIEM systems, log management |
| **Timestamping** | Proof of when actions occurred | Trusted time sources |

### Chapter 2: Authentication and Authorization

#### Access Control Process
| Component | Description | Examples |
|-----------|-------------|----------|
| **Identification** | User makes a claim of identity | Username, email address |
| **Authentication** | User proves identity claim | Password, biometrics, tokens |
| **Authorization** | System determines if user can perform action | Role-based permissions |
| **Accounting** | Records who performed which actions | Audit logs, activity tracking |

#### Multi-Factor Authentication (MFA)
| Factor Type | Description | Examples |
|-------------|-------------|----------|
| **Something You Know** | Knowledge-based authentication | Passwords, PINs, security questions |
| **Something You Have** | Physical possession | Smart cards, tokens, mobile devices |
| **Something You Are** | Biometric characteristics | Fingerprints, facial recognition, voice |

#### Password Security Requirements
| Requirement | Purpose | Implementation |
|-------------|---------|----------------|
| **Length** | Minimum character count | 8+ characters minimum |
| **Complexity** | Multiple character types | Uppercase, lowercase, numbers, symbols |
| **History** | Prevent password reuse | Last 5-10 passwords blocked |
| **Expiration** | Force periodic changes | 90-day rotation |
| **Reset** | User-initiated changes | Self-service password reset |

### Chapter 3: Privacy

#### Privacy Management Framework (PMF) Principles
| Principle | Description |
|-----------|-------------|
| **Management** | Establish privacy governance structure |
| **Agreement, Notice & Communication** | Clear privacy policies and consent |
| **Collection & Creation** | Minimize data collection |
| **Use, Retention & Disposal** | Purpose limitation and data lifecycle |
| **Access** | Individual access rights |
| **Disclosure to Third Parties** | Third-party sharing controls |
| **Security for Privacy** | Technical safeguards |
| **Data Integrity & Quality** | Accurate and complete data |
| **Monitoring & Enforcement** | Compliance oversight |

#### Personal Information Types
| Type | Definition | Examples |
|------|------------|----------|
| **PII** | Personally Identifiable Information | Name, SSN, address, phone |
| **PHI** | Protected Health Information | Medical records, health data |

### Chapter 4: Risk Management

#### Risk Categories
| Category | Description | Examples |
|----------|-------------|----------|
| **Internal Risks** | Originate within organization | Employee misconduct, system failures |
| **External Risks** | Threat originates outside organization | Cyber attacks, natural disasters |
| **Multiparty Risks** | Shared among multiple organizations | Supply chain, cloud services |

#### Risk Assessment Methods
| Method | Description | Characteristics |
|--------|-------------|----------------|
| **Qualitative** | Subjective judgments | Low/Medium/High categories |
| **Quantitative** | Objective numeric ratings | Probability percentages, dollar amounts |

#### Risk Treatment Options
| Option | Description | When to Use |
|--------|-------------|-------------|
| **Avoid** | Eliminate the risk entirely | High impact, low benefit activities |
| **Transfer** | Shift risk to another party | Insurance, outsourcing |
| **Mitigate** | Reduce likelihood or impact | Security controls, redundancy |
| **Accept** | Acknowledge and monitor | Low impact, high cost to control |

#### Risk Assessment Matrix
| Impact/Likelihood | Low | Medium | High |
|-------------------|-----|--------|------|
| **Low** | Accept | Mitigate | Mitigate |
| **Medium** | Accept | Mitigate | Transfer |
| **High** | Mitigate | Transfer | Avoid |

#### Risk Profile Components
| Component | Description |
|-----------|-------------|
| **Inherent Risk** | Risk level before controls |
| **Residual Risk** | Risk level after controls |
| **Control Risk** | New risks introduced by controls |

### Chapter 5: Security Controls

#### Control Classification by Purpose
| Purpose | Description | Examples |
|---------|-------------|----------|
| **Preventive** | Stop security issues before they occur | Firewalls, access controls |
| **Detective** | Identify potential security breaches | IDS, monitoring systems |
| **Recovery** | Remediate security issues after occurrence | Backups, incident response |

#### Control Classification by Mechanism
| Mechanism | Description | Examples |
|-----------|-------------|----------|
| **Technical** | Technology-based controls | Encryption, authentication systems |
| **Administrative** | Process and policy controls | Security policies, training |
| **Physical** | Physical world controls | Locks, security guards, fences |

#### Access Control Methods Summary
| Action | Description |
|--------|-------------|
| **Prevent** | Strong authentication, least privilege, RBAC |
| **Correct** | Revoke access, update policies, patch vulnerabilities |
| **Detect** | Monitor logs, anomaly detection, real-time alerts |
| **Control** | ACLs, MAC, DAC, ABAC |
| **Enforce** | Policy enforcement, data encryption |

### Chapter 6: Ethics

#### ISC2 Code of Ethics - Four Canons
| Canon | Requirement | Who Can File Complaint |
|-------|-------------|----------------------|
| **Canon 1** | Protect society, common good, public trust, infrastructure | Anyone |
| **Canon 2** | Act honorably, honestly, justly, responsibly, legally | Anyone |
| **Canon 3** | Provide diligent and competent service to principals | Employer/client only |
| **Canon 4** | Advance and protect the profession | Any certified professional |

### Chapter 7: Security Governance Processes

#### Security Documentation Types
| Document Type | Description | Compliance |
|---------------|-------------|------------|
| **Policies** | High-level security principles | Mandatory |
| **Standards** | Specific security requirements | Mandatory |
| **Guidelines** | Recommended security practices | Optional |
| **Procedures** | Step-by-step security processes | Mandatory |

#### Governance Terms Comparison
| Term | Description |
|------|-------------|
| **Regulation** | Rules established by authorities to control conduct within a specific area (e.g., law) |
| **Policy** | A set of principles or rules that guide decisions and actions within an organization |
| **Standard** | Established criteria or norms to ensure consistency and quality |
| **Guideline** | Recommendations or advice that help achieve desired outcomes but are not mandatory |
| **Procedure** | Detailed steps or processes to be followed to carry out specific tasks |
| **Compliance** | Adherence to laws, regulations, standards, or policies |

#### Key Regulations
| Regulation | Scope | Focus |
|------------|-------|-------|
| **GDPR** | EU residents' personal data | Privacy and data protection |
| **PCI DSS** | Credit/debit card information | Payment card security |

---

## Domain 2: Business Continuity, Disaster Recovery & Incident Response

### Chapter 8: Business Continuity

#### Business Continuity Components
| Component | Description | Purpose |
|-----------|-------------|---------|
| **Business Impact Analysis (BIA)** | Identifies mission-essential functions and critical IT systems | Prioritize recovery efforts |
| **Single Point of Failure Analysis** | Identifies components whose failure would cause system outage | Risk assessment |
| **High Availability (HA)** | Multiple systems to protect against failures | Redundancy |
| **Fault Tolerance (FT)** | Single system resilience to technical failures | System hardening |

#### Common System Failure Points
| Component | Failure Risk | Mitigation |
|-----------|-------------|-----------|
| **Power Supply** | High | UPS, backup generators |
| **Storage** | High | RAID, backups |
| **Network Connection** | High | Redundant connections |

### Chapter 9: Disaster Recovery

#### Recovery Objectives
| Objective | Definition | Purpose |
|-----------|------------|---------|
| **Recovery Time Objective (RTO)** | Time to restore service after disruption | Service restoration timeline |
| **Recovery Point Objective (RPO)** | Maximum data loss time period | Data backup frequency |
| **Recovery Service Level (RSL)** | Percentage of service availability during disaster | Service continuity level |

#### Backup Types
| Type | Description | Advantages | Disadvantages |
|------|-------------|------------|---------------|
| **Full Backup** | Complete copy of all data | Complete recovery | Time and storage intensive |
| **Snapshot** | Point-in-time copy using hardware | Fast creation | Platform dependent |
| **Differential** | Changes since last full backup | Moderate speed | Growing size |
| **Incremental** | Changes since last backup | Fast and efficient | Complex recovery |
| **Mirror Backup** | Real-time exact copy without compression | Quick access | No versioning |
| **Cloud Backup** | Remote cloud storage | Off-site protection | Internet dependent |
| **Local Backup** | Physical device storage | Fast recovery | On-site risk |
| **Hybrid Backup** | Combination of local and cloud | Best of both worlds | Complex management |
| **Snapshot Backup** | System state at specific time | Virtual environment friendly | Limited retention |

#### Recovery Site Types
| Site Type | Description | Recovery Time | Cost |
|-----------|-------------|---------------|------|
| **Hot Site** | Fully operational, ready to run | Minimal (near-zero downtime) | High |
| **Warm Site** | Hardware/software ready, not running | Moderate (hours to days) | Moderate |
| **Cold Site** | Empty facility, basic infrastructure | Long (days to weeks) | Low |

### Chapter 10: Incident Response

#### NIST Incident Response Stages
| Stage | Description | Key Activities |
|-------|-------------|----------------|
| **Preparation** | Establish incident response capability | Team formation, procedures, tools |
| **Detection & Analysis** | Identify and assess security incidents | Monitoring, alerting, triage |
| **Containment** | Limit damage from incident | Isolation, eradication |
| **Eradication & Recovery** | Remove threat and restore systems | Cleanup, restoration |
| **Post-Incident Activity** | Learn from incident | Lessons learned, documentation |

#### Incident Response Timeline
| Phase | Duration | Key Activities |
|-------|----------|----------------|
| **Preparation** | Ongoing | Team setup, procedures |
| **Detection** | Minutes-Hours | Alert triage, initial assessment |
| **Containment** | Hours | Damage limitation |
| **Eradication** | Hours-Days | Threat removal |
| **Recovery** | Days-Weeks | Service restoration |
| **Lessons Learned** | Weeks | Documentation, improvements |

#### Incident Response Team Roles
| Role | Responsibilities |
|------|------------------|
| **Management** | Decision making, resource allocation |
| **Information Security** | Technical response, threat analysis |
| **Physical Security** | Facility access, evidence collection |
| **Legal Counsel** | Compliance, liability assessment |
| **Public Relations** | External communications |
| **Human Resources** | Employee-related incidents |
| **Technical SMEs** | Specialized technical knowledge |

#### Key Response Priorities
| Priority | Action | Rationale |
|----------|--------|-----------|
| **First Priority** | Contain damage quickly | Minimize impact |
| **Second Priority** | Preserve evidence | Investigation needs |
| **Third Priority** | Restore services | Business continuity |

---

## Domain 3: Access Controls Concepts

### Chapter 11: Physical Access Controls

#### Sensitive Facilities Requiring Controls
| Facility Type | Security Requirements |
|---------------|----------------------|
| **Data Centers** | High security, environmental controls |
| **Server Rooms** | Restricted access, monitoring |
| **Media Storage** | Climate control, access logging |
| **Evidence Storage** | Chain of custody, secure access |
| **Wiring Closets** | Network security, physical protection |
| **Cable Distribution** | Infrastructure protection |

#### Crime Prevention Through Environmental Design (CPTED)
| Goal | Description | Implementation |
|------|-------------|----------------|
| **Natural Surveillance** | Design for visibility | Lighting, clear sight lines |
| **Natural Access Control** | Design to guide movement | Fencing, landscaping |
| **Natural Territorial Reinforcement** | Define boundaries | Signs, barriers, ownership |

#### Visitor Access Controls
| Control | Description |
|---------|-------------|
| **Authorization Procedures** | Who can approve visitor access |
| **Behavior Guidelines** | Visitor conduct requirements |
| **Access Logging** | Record all visitor activity |
| **Badge Identification** | Clear visitor status marking |

#### Multi-Person Controls
| Control | Description | Use Case |
|---------|-------------|---------|
| **Two-Person Integrity** | Two people present for access | Valuable item storage |
| **Two-Person Control** | Two people required for action | Sensitive operations |

### Chapter 12: Logical Access Controls

#### Access Control Principles
| Principle | Description | Implementation |
|-----------|-------------|----------------|
| **Least Privilege** | Minimum necessary permissions | Role-based access |
| **Segregation of Duties** | No single person has conflicting permissions | Separation of responsibilities |
| **Non-repudiation** | Cannot deny taking action | Digital signatures, logs |

#### Access Control Models
| Model | Description | Key Features |
|-------|-------------|-------------|
| **Discretionary Access Control (DAC)** | Resource owner controls access | • Resource owner grants access<br>• Permissions can be transferred<br>• Least restrictive |
| **Mandatory Access Control (MAC)** | System-enforced restrictions based on rules | • Access decisions made by system<br>• Common in high-security environments<br>• Users can't change permissions |
| **Role-Based Access Control (RBAC)** | Access based on organizational roles | • Users assigned to roles<br>• Roles have predefined permissions<br>• Role hierarchy possible |
| **Attribute-Based Access Control (ABAC)** | Access based on attributes (time, location, device) | • Fine-grained access control<br>• Policies define rules based on attributes |
| **Rule-Based Access Control** | Access based on predefined rules | • Similar to MAC but customizable<br>• Focuses on policies and rules |
| **Identity-Based Access Control (IBAC)** | Access based on individual user identities | • Authentication is critical<br>• Access granted based on identity verification |

#### Subject-Object Process
| Component | Description | Example |
|-----------|-------------|---------|
| **Subject** | The entity requesting access or performing an action | User, Process, System |
| **Object** | The resource being accessed or modified | File, Database, Network Resource |
| **Process** | The action performed by the subject on the object | Read, Write, Execute, Modify |

---

## Domain 4: Network Security

### Chapter 13: Computer Networking

#### OSI Model Layers
| Layer | Name | Function | Examples |
|-------|------|----------|----------|
| **7** | Application | Interface for user applications; provides network services | HTTP, FTP, SMTP |
| **6** | Presentation | Data translation, encryption, compression | Encryption, compression |
| **5** | Session | Manages sessions and controls data exchange | Session establishment |
| **4** | Transport | Ensures reliable data transfer (TCP/UDP) | TCP, UDP |
| **3** | Network | Routing, logical addressing (IP) | IP, ICMP |
| **2** | Data Link | Physical addressing, error detection, framing | Ethernet, Wi-Fi |
| **1** | Physical | Transmits raw bits over physical medium | Cables, signals |

#### TCP/IP Protocol Suite
| Component | Purpose | Examples |
|-----------|---------|----------|
| **Internet Protocol (IP)** | Network layer routing | IPv4, IPv6 |
| **Transmission Control Protocol (TCP)** | Reliable transport | Web browsing, email |
| **User Datagram Protocol (UDP)** | Fast transport | Video streaming, gaming |

#### TCP vs UDP Comparison
| Feature | UDP | TCP |
|---------|-----|-----|
| **Protocol Type** | Connectionless | Connection-oriented |
| **Reliability** | Unreliable (no error checking) | Reliable (error checking and correction) |
| **Speed** | Faster due to less overhead | Slower due to connection setup and error checking |
| **Connection** | No connection establishment required | Requires connection setup (handshake) |
| **Flow Control** | No flow control | Yes, through flow control mechanisms |
| **Use Case** | Streaming, gaming, DNS, VoIP | File transfer, web browsing, email |
| **Packet Order** | No guarantee of order | Guarantees in-order delivery |
| **Header Size** | Smaller (8 bytes) | Larger (20 bytes) |
| **Transmission** | Sends data without acknowledgment | Ensures data delivery with ACKs |

#### IP Addressing
| Version | Format | Example | Address Space |
|---------|--------|---------|---------------|
| **IPv4** | Dotted quad notation | 192.168.1.1 | 32-bit (4.3 billion) |
| **IPv6** | Hexadecimal groups | 2001:0db8:85a3:0000:0000:8a2e:0370:7334 | 128-bit (340 undecillion) |

#### Subnet Masks (CIDR Notation)
| CIDR Notation | Subnet Mask | Number of Usable Hosts | IP Address Class |
|---------------|-------------|----------------------|------------------|
| **/8** | 255.0.0.0 | 16,777,214 | Class A |
| **/16** | 255.255.0.0 | 65,534 | Class B |
| **/24** | 255.255.255.0 | 254 | Class C |
| **/32** | 255.255.255.255 | 1 (only the specific IP address) | (Specific Host) |

#### Common Network Ports
| Port | Protocol | Service | Description |
|------|----------|---------|-------------|
| **80** | HTTP | Web traffic | Unsecured web browsing |
| **443** | HTTPS | Secure web traffic | Encrypted web browsing |
| **22** | SSH | Secure shell | Remote server access |
| **25** | SMTP | Email sending | Simple Mail Transfer Protocol |
| **21** | FTP | File transfer | File Transfer Protocol |
| **110** | POP3 | Email retrieval | Post Office Protocol |
| **143** | IMAP | Email retrieval | Internet Message Access Protocol |
| **53** | DNS | Domain name system | Domain name resolution |
| **3389** | RDP | Remote desktop | Remote desktop protocol |

#### Network Ports by Range
| Port Range | Usage | Examples |
|------------|-------|----------|
| **0-1023** | Well-known ports | HTTP (80), HTTPS (443) |
| **1024-49151** | Registered ports | Custom applications |
| **49152-65535** | Dynamic ports | Temporary connections |

#### Wi-Fi Security
| Technology | Description | Security Level |
|------------|-------------|---------------|
| **Preshared Keys** | Shared password | Basic |
| **Enterprise Authentication** | RADIUS/802.1X | High |
| **Captive Portals** | Web-based authentication | Medium |
| **WPA2/WPA3** | Encryption protocols | High |

### Chapter 14: Network Threats and Attacks

#### Malware Types
| Malware Type | Description |
|--------------|-------------|
| **Virus** | Attaches to files or programs, spreads to other systems |
| **Worm** | Self-replicating and spreads over networks without user input |
| **Trojan Horse** | Disguised as legitimate software, causes data theft or control |
| **Ransomware** | Locks or encrypts data and demands payment for access |
| **Spyware** | Monitors user activity, often for identity theft |
| **Adware** | Displays unwanted ads, may slow down systems |
| **Rootkit** | Hides its presence, provides unauthorized system control |
| **Keylogger** | Records keystrokes to capture sensitive information |
| **Botnet** | Network of infected devices used for malicious activities |
| **Backdoor** | Creates unauthorized access to a system for attackers |

#### Attack Types
| Attack | Description | Impact |
|--------|-------------|--------|
| **Man-in-the-Middle (MitM)** | Intercepts communications | Data theft, session hijacking |
| **Denial-of-Service (DoS)** | Single source overwhelms target | Service unavailability |
| **Distributed DoS (DDoS)** | Multiple sources attack target | Large-scale service disruption |

### Chapter 15: Threat Identification and Prevention

#### Intrusion Detection/Prevention Systems
| Type | Scope | Function |
|------|-------|----------|
| **Host-based IDS/IPS** | Individual devices | File monitoring, system calls |
| **Network-based IDS/IPS** | Network traffic | Packet analysis, traffic patterns |

#### Security Technologies
| Technology | Purpose | Function |
|------------|---------|----------|
| **Firewalls** | Network security guard | Traffic filtering, access control |
| **IDS** | Threat detection | Monitoring, alerting |
| **IPS** | Threat prevention | Blocking, response |

### Chapter 16: Network Security Infrastructure

#### Firewall Types
| Firewall Type | Description | Pros | Cons |
|---------------|-------------|------|------|
| **Packet Filtering Firewall** | Inspects packets based on IP address, port, and protocol | Simple, fast, low resource usage | Limited filtering, no state tracking |
| **Stateful Inspection Firewall** | Tracks the state of active connections and makes decisions based on state | More secure than packet filtering | Slower than packet filtering, higher resource usage |
| **Proxy Firewall** | Acts as an intermediary between users and the services they wish to access | Provides deep inspection, hides internal network | Can introduce latency, complex configuration |
| **Next-Generation Firewall (NGFW)** | Combines traditional firewall features with additional features like deep packet inspection, intrusion prevention, and application awareness | High security, advanced features | Resource-intensive, complex to configure |
| **Web Application Firewall (WAF)** | Specifically protects web applications by filtering HTTP traffic | Protects against web-based attacks (e.g., XSS, SQL injection) | Limited to web traffic, doesn't protect other types of network traffic |
| **Circuit-Level Gateway** | Monitors the handshake between packets to ensure sessions are legitimate | Faster than application-level firewalls | Limited inspection, lacks deep packet inspection |
| **Hybrid Firewall** | Combines features of multiple firewall types (e.g., stateful and proxy) | Provides comprehensive security | Complex configuration, resource-heavy |

#### Firewall Comparison
| Firewall Type | Description | Functionality | Pros | Cons |
|---------------|-------------|---------------|------|------|
| **Web Filter** | Filters web traffic based on content, URL, or domain | Blocks access to malicious websites or inappropriate content | Effective against malicious websites, content control | Can block legitimate websites, limited to web traffic |
| **Packet Filter** | Inspects individual packets based on predefined rules (IP, port, protocol) | Provides basic firewalling by allowing or blocking traffic based on header information | Fast, simple, low resource usage | Limited in functionality, no deep inspection |
| **Proxy Firewall** | Acts as an intermediary between users and services, filtering web requests | Provides additional security by hiding internal IPs and inspecting full content of requests | Hides internal network, deep packet inspection | Can introduce latency, complex setup |
| **Stateful Inspection** | Tracks the state of connections, ensuring packets are part of an established connection | Inspects traffic in context, allowing or blocking based on the connection state | More secure than packet filtering, tracks sessions | Higher resource usage, slower than packet filtering |

#### Data Center Management
| Component | Requirements | Controls |
|-----------|--------------|---------|
| **Environmental** | Temperature, humidity | HVAC systems |
| **Fire Suppression** | Fire detection and control | Sprinklers, gas systems |
| **Physical Security** | Access control | Locks, surveillance |

#### Network Devices
| Device | Function | Security Role |
|--------|----------|--------------|
| **Switches** | Local network connectivity | VLANs, port security |
| **Routers** | Inter-network routing | Access control lists |
| **Firewalls** | Traffic filtering | Security policy enforcement |

#### Network Zones
| Zone | Purpose | Security Level |
|------|---------|---------------|
| **Internet** | External connectivity | Low trust |
| **DMZ** | Public-facing services | Medium trust |
| **Intranet** | Internal systems | High trust |

#### Network Access Control (NAC)
| Function | Description |
|----------|-------------|
| **Device Verification** | Check system compliance |
| **User Authentication** | Verify user identity |
| **Network Authorization** | Grant appropriate access |

### Chapter 17: Cloud Computing

#### Cloud Deployment Models
| Model | Description | Access | Examples |
|-------|-------------|--------|----------|
| **Public Cloud** | Shared infrastructure | Open | AWS, Azure, Google Cloud |
| **Private Cloud** | Dedicated infrastructure | Restricted | Internal data centers |
| **Community Cloud** | Shared by specific community | Shared/Restricted | Academic networks, specialized forums |
| **Hybrid Cloud** | Mix of deployment models | Restricted/Shared | Cloud storage solutions |

#### Cloud Service Models
| Model | Description | Key Features | Examples |
|-------|-------------|-------------|----------|
| **Infrastructure as a Service (IaaS)** | Provides virtualized computing resources over the internet | • Offers virtual machines, storage, and networks<br>• Users manage operating systems, applications, and data | AWS EC2, Microsoft Azure |
| **Platform as a Service (PaaS)** | Provides a platform allowing customers to develop, run, and manage applications | • Includes development tools, middleware, and databases<br>• Users focus on app development, not infrastructure management | Google App Engine, Microsoft Azure App Services |
| **Software as a Service (SaaS)** | Delivers software applications over the internet on a subscription basis | • Fully managed applications accessible via web browsers<br>• No infrastructure or platform management required | Google Workspace, Microsoft Office 365, Salesforce |
| **Function as a Service (FaaS)** | A serverless computing model where developers run code in response to events | • No need to manage servers<br>• Code execution based on triggers (e.g., HTTP requests) | AWS Lambda, Google Cloud Functions |
| **Container as a Service (CaaS)** | Provides container orchestration services for managing containers at scale | • Users manage applications within containers | Kubernetes, Docker Swarm on cloud platforms |
| **Database as a Service (DBaaS)** | A cloud service offering database management systems | • Fully managed database services (SQL, NoSQL) | Amazon RDS, Google Cloud SQL, Azure SQL Database |

#### Cloud Management
| Approach | Description | Benefits |
|----------|-------------|----------|
| **Automation** | Automated resource management | Efficiency, consistency |
| **Orchestration** | Coordinated resource deployment | Scalability, reliability |
| **Infrastructure as Code (IaC)** | Scripted resource creation | Version control, repeatability |

---

## Domain 5: Security Operations

### Chapter 18: Encryption

#### Encryption Concepts
| Concept | Description | Purpose |
|---------|-------------|---------|
| **Encryption** | Transform plaintext to ciphertext | Data protection |
| **Decryption** | Transform ciphertext to plaintext | Data access |
| **Key** | Secret value for encryption/decryption | Algorithm parameter |

#### Data Protection Types
| Data Type | Description | Examples | Security |
|-----------|-------------|----------|----------|
| **Data at Rest** | Data stored on a device or server, not actively being used | Files, databases, backups | Encryption, access control |
| **Data in Transit** | Data being transferred over a network | Emails, file transfers, API requests | Encryption (SSL/TLS), VPN, firewalls |

#### Encryption Types
| Type | Description | Example | Use Case |
|------|-------------|---------|---------|
| **Symmetric** | Same key for both encryption and decryption | AES, DES | Secure communication with shared key |
| **Asymmetric** | Uses public and private keys for encryption and decryption | RSA, ECC | Secure communication without sharing the key |
| **Hashing** | Converts data into a fixed-size string, cannot be reversed | SHA-256, MD5 | Verifying data integrity, password storage |
| **Digital Signature (DS)** | A mathematical scheme for verifying data authenticity and integrity | RSA, DSA | Verifying authenticity of messages/documents, digital contracts |

#### Hash Functions
| Characteristic | Description | Purpose |
|----------------|-------------|---------|
| **One-way** | Cannot reverse the function | Password storage |
| **Fixed-length** | Consistent output size | Data integrity |
| **Unique** | Different inputs = different outputs | Digital signatures |

### Chapter 19: Data Handling

#### Data Lifecycle Management
| Phase | Activities | Security Requirements |
|-------|------------|----------------------|
| **Creation** | Data generation | Classification, labeling |
| **Storage** | Data retention | Access controls, encryption |
| **Use** | Data processing | Authorization, monitoring |
| **Sharing** | Data distribution | Encryption, access logs |
| **Archiving** | Long-term storage | Secure storage, retention policies |
| **Destruction** | Data disposal | Secure deletion, media sanitization |

#### Data Classification Schemes
| Military Classification | Business Classification | Handling Requirements |
|------------------------|------------------------|----------------------|
| **Top Secret** | Highly Sensitive | Strictest controls |
| **Secret** | Sensitive | High security |
| **Confidential** | Internal | Moderate security |
| **Unclassified** | Public | Basic protection |

#### Data Labeling Standards
| Requirement | Purpose | Implementation |
|-------------|---------|----------------|
| **Standardized Labels** | Consistent recognition | Organization-wide format |
| **Clear Markings** | Obvious classification | Visual indicators |
| **Handling Instructions** | Proper procedures | Label-based guidance |

### Chapter 20: Logging and Monitoring

#### Log Management Benefits
| Benefit | Description | Use Cases |
|---------|-------------|----------|
| **Accountability** | Attribute activities to sources | User tracking, audit trails |
| **Traceability** | Find related events | Incident investigation |
| **Auditability** | Maintain accurate records | Compliance, forensics |

#### SIEM System Capabilities
| Capability | Description | Benefits |
|------------|-------------|----------|
| **Centralized Collection** | Single log repository | Comprehensive view |
| **Data Integrity** | Tamper-resistant logs | Evidence preservation |
| **Correlation Analysis** | Pattern recognition | Threat detection |
| **AI/ML Integration** | Automated analysis | Reduced false positives |

### Chapter 21: Configuration Management

#### Configuration Management Components
| Component | Description | Security Benefits |
|-----------|-------------|------------------|
| **Documentation** | System configuration records | Change tracking |
| **Change Control** | Managed system modifications | Unauthorized change prevention |
| **Baselines** | Known good configurations | Deviation detection |

#### Baseline Management
| Activity | Purpose | Security Value |
|----------|---------|---------------|
| **Baseline Creation** | Document system state | Reference point |
| **Baseline Comparison** | Detect unauthorized changes | Security monitoring |
| **Baseline Updates** | Maintain current reference | Change management |

#### Update and Patch Management
| Activity | Purpose | Security Impact |
|----------|---------|----------------|
| **Vulnerability Assessment** | Identify security gaps | Risk reduction |
| **Patch Testing** | Verify patch compatibility | System stability |
| **Patch Deployment** | Apply security fixes | Vulnerability mitigation |

### Chapter 22: Best Practice Security Policies

#### Security Policy Types
| Policy Type | Purpose | Key Elements |
|-------------|---------|--------------|
| **Acceptable Use Policy (AUP)** | Define technology usage boundaries | Personal use limits, consequences |
| **Data Handling Policy** | Protect sensitive information | Classification, procedures |
| **Password Policy** | Ensure strong authentication | Complexity, expiration |
| **BYOD Policy** | Manage personal devices | Security requirements, data protection |
| **Privacy Policy** | Communicate data practices | Collection, use, sharing |
| **Change Management Policy** | Control system modifications | Approval process, rollback plans |

### Chapter 23: Security Awareness Training

#### Social Engineering Tactics
| Tactic | Description | Countermeasures |
|--------|-------------|----------------|
| **Authority** | Exploit respect for authority | Verify identity, question requests |
| **Trust** | Build false relationships | Maintain skepticism |
| **Intimidation** | Create fear or urgency | Stay calm, verify threats |
| **Consensus** | Follow the crowd mentality | Independent verification |
| **Scarcity** | Limited availability pressure | Resist urgency, research |
| **Familiarity** | Exploit personal connections | Verify unexpected contacts |

#### Training Program Components
| Component | Description | Target Audience |
|-----------|-------------|----------------|
| **General Cybersecurity** | Basic security principles | All employees |
| **Role-Specific Training** | Job-related security requirements | Department-specific |
| **Social Engineering Awareness** | Threat recognition | All employees |
| **Password Security** | Authentication best practices | All users |
| **Incident Reporting** | Security incident procedures | All employees |

#### Training Effectiveness
| Factor | Description | Impact |
|--------|-------------|--------|
| **Continuous Updates** | Keep content current | Relevance to threats |
| **Engagement** | Interactive, memorable content | Knowledge retention |
| **Testing** | Verify understanding | Effectiveness measurement |
| **Reinforcement** | Regular reminders | Behavior change |

---

## Quick Reference Tables

### Network Security Controls
| Layer | Controls | Purpose |
|-------|----------|---------|
| **Physical** | Locks, cameras, guards | Prevent physical access |
| **Network** | Firewalls, IDS/IPS | Traffic filtering |
| **Host** | Antivirus, HIDS | Endpoint protection |
| **Application** | Input validation, WAF | Application security |
| **Data** | Encryption, DLP | Data protection |

### Cloud Service Model Comparison
| Model | Control Level | Management Responsibility | Examples |
|-------|--------------|--------------------------|----------|
| **IaaS** | High | Infrastructure management | AWS EC2, Azure VMs |
| **PaaS** | Medium | Application development | Heroku, AWS Elastic Beanstalk |
| **SaaS** | Low | Application usage | Gmail, Salesforce |
| **FaaS** | Minimal | Function development | AWS Lambda, Google Cloud Functions |

### Encryption Algorithm Comparison
| Algorithm Type | Key Management | Speed | Security Level | Use Case |
|----------------|----------------|-------|---------------|----------|
| **AES (Symmetric)** | Shared key | Fast | High | Bulk data encryption |
| **RSA (Asymmetric)** | Public/private pair | Slow | High | Key exchange, digital signatures |
| **SHA-256 (Hash)** | No key needed | Very fast | High | Data integrity, password hashing |

### Incident Response Priority Matrix
| Incident Type | Priority | Response Time | Team Involvement |
|---------------|----------|---------------|------------------|
| **Data Breach** | Critical | Immediate | Full team |
| **Malware Outbreak** | High | Within hours | Security + IT |
| **Phishing Campaign** | Medium | Within day | Security team |
| **Policy Violation** | Low | Within week | HR + Security |

### Security Control Effectiveness
| Control Type | Prevention | Detection | Recovery |
|--------------|------------|-----------|----------|
| **Technical** | High | High | Medium |
| **Administrative** | Medium | Medium | High |
| **Physical** | High | Low | Low |

---

*This comprehensive cheatsheet covers all key concepts from the ISC2 CC exam organized by domains. Remember to review the official study materials and practice with sample questions for comprehensive exam preparation.* 