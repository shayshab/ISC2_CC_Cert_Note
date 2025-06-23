# ISC2 Certified in Cybersecurity (CC) Complete Exam Cheatsheet - Part 1

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