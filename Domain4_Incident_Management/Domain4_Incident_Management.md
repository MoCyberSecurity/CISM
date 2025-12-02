# Domain 4: Information Security Incident Management

**Weight: 30% of the CISM exam**

Domain 4 focuses on building and operating a **strategic incident management capability** that protects the organization from disruption, ensures rapid recovery, and preserves trust, reputation, and regulatory compliance.

The ultimate objective of this domain is to **minimize business impact and restore operations as quickly and safely as possible**.

---

## Incident Management vs Incident Response

### Incident Management (Strategic Level)
Incident management is the **governance and program-level capability** that ensures the organization is prepared for security incidents.

It includes:
- Planning and documentation
- Resource allocation
- Training and exercises
- Metrics and continuous improvement
- Executive oversight and coordination

This function answers:  
**“Is the organization ready to respond effectively when something happens?”**

---

### Incident Response (Operational Level)
Incident response is the **hands-on execution** that occurs once an attack or disruption is identified.

Core phases align with SANS/NIST frameworks:

1. **Preparation** – policies, tools, training, readiness
2. **Identification** – detecting and verifying an incident
3. **Containment** – isolating the threat and protecting evidence
4. **Eradication** – removing root cause
5. **Recovery** – restoring operations and data
6. **Lessons Learned** – post-incident review and updates

This function answers:  
**“What do we do right now?”**

---

### Key Priorities for All Incidents

Incident handling decisions should always prioritize:

- Protection of **human life and safety**
- Minimizing system downtime and service disruption
- Preserving the **CIA triad**:
  - Confidentiality
  - Integrity
  - Availability
- Preventing recurrence
- Meeting regulatory and contractual requirements
- Protecting organizational reputation

---

## Incident Response Plan (IRP)

The **Incident Response Plan** defines how incidents are detected, managed, escalated, and resolved.

### Core Components

- **Policies & Standards**  
  Define scope, objectives, and authority of response teams.

- **Teams & Staffing**  
  Roles, responsibilities, training requirements, and on-call coverage.

- **Notification Procedures**  
  Automated alerts and clear escalation pathways.

- **Integration**  
  Alignment between:
  - IRP (response actions)
  - BCP (business continuity)
  - DRP (technical recovery)

---

### Incident Handling Lifecycle

| Phase | Purpose |
|------|-----------|
| **Preparation** | Training, tools, playbooks |
| **Identification** | Detect and confirm active incidents |
| **Containment** | Isolate threats and preserve evidence |
| **Eradication** | Remove malicious components |
| **Recovery** | Restore systems to meet RTO/RPO targets |
| **Lessons Learned** | Review, update controls and procedures |

---

## Business Impact Analysis (BIA)

The **Business Impact Analysis** identifies how disruptions affect the organization and establishes recovery priorities.

### Purpose

- Determine consequences of downtime or data loss.
- Identify which business functions must be restored first.
- Provide measurable targets for continuity and recovery plans.

---

### Key BIA Outputs

- **Critical Business Functions**
- **Downtime tolerance thresholds**
- **Resource dependencies**
- **Recovery Time Objective (RTO)**  
  Maximum acceptable time to restore services.

- **Recovery Point Objective (RPO)**  
  Maximum acceptable amount of data loss (time gap).

---

### BIA Process

1. Identify business functions.
2. Map system and vendor dependencies.
3. Rank process criticality.
4. Define RTO and RPO.
5. Evaluate impacts (financial, operational, reputational, regulatory).
6. Compile findings for BCP and DRP development.

---

## Business Continuity Plan (BCP)

The **Business Continuity Plan** ensures that essential business operations continue during major disruptions.

### Scope

BCP integrates:
- Incident response actions
- Disaster recovery methods
- Crisis communications

---

### Key BCP Components

- Alignment with BIA RTO/RPO targets.
- Clearly assigned recovery roles.
- Stakeholder communication procedures tailored to:
  - Employees
  - Customers
  - Regulators
  - Media

---

### High-Availability Strategies

- Redundant infrastructure
- Load-balanced environments
- Clustered systems
- Geographic separation
- Cloud continuity options

---

### Risk Transfer

Insurance supports financial mitigation, not prevention:

- Cyber breach and ransomware policies.
- Coverage depends on compliance posture and exclusions.

---

## Disaster Recovery Plan (DRP)

The **Disaster Recovery Plan** focuses on restoring IT systems and data following major disruptions.

### DRP Workflow

1. Conduct risk assessment and BIA
2. Define recovery strategies
3. Document technical recovery procedures
4. Train response teams
5. Test plans regularly

---

### Recovery Site Strategies

| Site Type | Characteristics |
|------------|------------------|
| **Cold Site** | No systems; lowest cost, longest recovery |
| **Warm Site** | Hardware pre-installed; moderate recovery |
| **Hot Site** | Fully operational failover environment |
| **Cloud DR / DRaaS** | On-demand cloud recovery services |
| **Mutual Assistance** | Shared arrangements (high-risk method) |

**Guidance:**  
Recovery sites should typically be located **300+ miles away** to avoid regional disruptions.

---

## Incident Classification & Categorization

### Categorization  
Defines the **type of incident**:
- Malware infections
- DDoS attacks
- Data breaches
- System outages
- Hardware failure

---

### Classification  
Defines **severity and priority**:
- Critical
- High
- Medium
- Low

Severity drives:
- Resource allocation
- Escalation levels
- Notification requirements

---

### Escalation Procedures

Plans must clearly document:

- Escalation thresholds
- Executive approval authorities
- Backup contacts
- Stakeholder notification lists
- Secure communication channels

Stakeholders may include:
- Legal counsel
- HR
- Public relations
- Regulators
- Law enforcement

---

## Training, Testing, and Evaluation

### Training

- Role-based instruction for:
  - IT
  - SOC
  - Management
  - Help desk
- Regular scenario and tabletop drills

---

### Testing Types

| Test Type | Description |
|-----------|----------------|
| **Read-through** | Individual document review |
| **Tabletop** | Group scenario discussion |
| **Simulation** | Partial operational testing |
| **Parallel Test** | Backup systems operate alongside production |
| **Full Interruption** | Live failover testing (annual best practice) |

---

### Metrics

- **KPIs:**  
  Mean time to detect, respond, resolve incidents

- **KGIs:**  
  Strategic targets such as year-over-year reduction in incidents

Metrics validate:
- IRP effectiveness
- BCP/DR readiness
- Compliance with RTO/RPO requirements

---

### Continuous Improvement

- Post-incident and post-test reviews
- Documentation updates
- Plan adjustments for:
  - Business changes
  - New technologies
  - Emerging threats

---

## Common Program Challenges

- Lack of executive sponsorship
- Poor integration with business objectives
- Staff turnover and training gaps
- Ineffective crisis communication
- Overly complex recovery plans

---

## CISM Exam Strategy Tips

- Distinguish:
  - **Incident Management (governance) vs Incident Response (execution)**
- Understand differences between:
  - **RTO (time to restore) vs RPO (data loss limit)**
- Follow logical flow:
  **BIA → BCP → DRP**
- Focus on integration and business alignment rather than memorising frameworks.

---

## Visual Summary

- **Incident Management** = planning, governance, oversight.
- **Incident Response** = detection and operations.
- **BIA → BCP → DRP** = progressive resilience chain.
- **Categorization = Type** | **Classification = Severity**
- **Testing and metrics drive continuous improvement.**

- 
## Diagrams
- [Incident Management Framework](diagrams/incident-management-framework.mmd)
- [BIA → BCP → DRP Exam Flow Diagram](diagrams/exam-flow.mmd)

---

## Examples

- [Incident Response Playbook Example](examples/incident-response-playbook-example.md)
- [Business Continuity Plan Outline](examples/bcp-outline-example.md)
- [Disaster Recovery Site Selection](examples/dr-site-selection-example.md)
- [Incident Classification & Severity Matrix](examples/classification-severity-matrix.md)
