# ISC2 Certified in Cybersecurity (CC) Complete Exam Cheatsheet - Part 2

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