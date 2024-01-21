# IAC-01 - Identity & Access Management (IAM)
Mechanisms exist to facilitate the implementation of identification and access management controls.
## Control questions
Does the organization facilitate the implementation of identification and access management controls?
## Control maturity
### Not performed
There is no evidence of a capability to facilitate the implementation of identification and access management controls.
### Performed internally
Identification & Authentication (IAC) efforts are ad hoc and inconsistent. CMM Level 1 control maturity would reasonably expect all, or at least most, the following criteria to exist:
•	Identity & Access Management (IAM) is decentralized where Active Directory (AD), or a similar technology, may be used to centrally manage identities and permissions, but asset/process owners are authorized to operate a decentralized access control program for their specific systems, applications and services.
•	IAM controls are primarily administrative in nature (e.g., policies & standards) to manage accounts and permissions.
•	IT personnel identify and implement IAM cybersecurity & data privacy controls that are appropriate to address applicable statutory, regulatory and contractual requirements.
### Planned and tracked
Identification & Authentication (IAC) efforts are requirements-driven and formally governed at a local/regional level, but are not consistent across the organization. CMM Level 2 control maturity would reasonably expect all, or at least most, the following criteria to exist:
•	Logical Access Control (LAC) is decentralized (e.g., a localized/regionalized function) and uses non-standardized methods to implement secure and compliant practices.
•	IT/cybersecurity personnel identify cybersecurity & data privacy controls that are appropriate to address applicable statutory, regulatory and contractual requirements for logical access control. 
•	IT personnel:
o	Implement and maintain an Identity & Access Management (IAM) capability for all users to implement “least privileges” Role Based Access Control (RBAC) practices for the management of user, group and system accounts, including privileged accounts.
o	Govern IAM technologies via RBAC to prohibit privileged access by non-organizational users, unless there is an explicit support contract for privileged IT support services.
•	Active Directory (AD), or a similar technology, is primarily used to centrally manage identities and permissions with RBAC. Due to technical or business limitations, asset/process owners are empowered to operate a decentralized access control program for their specific systems, applications and services that cannot be integrated into AD.
•	IAM controls are primarily administrative in nature (e.g., policies & standards) to manage accounts and permissions.
### Well defined
Identification & Authentication (IAC) efforts are standardized across the organization and centrally managed, where technically feasible, to ensure consistency. CMM Level 3 control maturity would reasonably expect all, or at least most, the following criteria to exist:
•	The Chief Information Security Officer (CISO), or similar function, analyzes the organization’s business strategy to determine prioritized and authoritative guidance for logical access control practices.
•	The CISO, or similar function, develops a security-focused Concept of Operations (CONOPS) that documents management, operational and technical measures to apply defense-in-depth techniques across the enterprise for logical access control.
•	A Governance, Risk & Compliance (GRC) function, or similar function, provides governance oversight for the implementation of applicable statutory, regulatory and contractual cybersecurity & data privacy controls to protect the confidentiality, integrity, availability and safety of the organization’s applications, systems, services and data with regards to logical access control.
•	A steering committee is formally established to provide executive oversight of the cybersecurity & data privacy program, including logical access control.
•	An IT Asset Management (ITAM) function, or similar function:
o	Categorizes endpoint devices according to the data the asset stores, transmits and/ or processes and applies the appropriate technology controls to protect the asset and data that conform to industry-recognized standards for hardening (e.g., DISA STIGs, CIS Benchmarks or OEM security guides).
o	Uses a Configuration Management Database (CMDB), or similar tool, as the authoritative source of IT assets configured to perform integrity checking and alert on unauthorized configuration changes.
•	An Identity & Access Management (IAM) function, or similar function, centrally manages permissions and implements “least privileges” Role Based Access Control (RBAC) practices for the management of user, group and system accounts, including privileged accounts.
•	The Human Resources (HR) department governs personnel management operations and notifies IAM personnel of personnel role changes for RBAC-based provisioning and deprovisioning actions.
•	An IT infrastructure team, or similar function, ensures that statutory, regulatory and contractual cybersecurity & data privacy obligations are addressed to ensure secure configurations are designed, built and maintained.
•	Active Directory (AD), or a similar technology, is used to centrally manage identities and permissions. Only by exception due to a technical or business limitation are solutions authorized to operate a decentralized access control program for systems, applications and services.
### Quantitatively controllled
Identification & Authentication (IAC) efforts are metrics driven and provide sufficient management insight (based on a quantitative understanding of process capabilities) to predict optimal performance, ensure continued operations and identify areas for improvement. In addition to CMM Level 3 criteria, CMM Level 4 control maturity would reasonably expect all, or at least most, the following criteria to exist:
- 	Metrics reporting includes quantitative analysis of Key Performance Indicators (KPIs).
- 	Metrics reporting includes quantitative analysis of Key Risk Indicators (KRIs).
- 	Scope of metrics, KPIs and KRIs covers organization-wide cybersecurity & data privacy controls, including functions performed by third-parties.
- 	Organizational leadership maintains a formal process to objectively review and respond to metrics, KPIs and KRIs (e.g., monthly or quarterly review).
- 	Based on metrics analysis, process improvement recommendations are submitted for review and are handled in accordance with change control processes.
- 	Both business and technical stakeholders are involved in reviewing and approving proposed changes.
### Continuously improving
See SP-CMM4. SP-CMM5 is N/A, since a continuously-improving process is not necessary to facilitate the implementation of identification and access management controls.
## Mapped framework controls
### SOC 2
- [CC6.1](../soc2/cc61.md)