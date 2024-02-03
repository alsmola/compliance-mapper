# END-13.2 - Notice of Collection
Mechanisms exist to notify individuals that Personal Data (PD) is collected by sensors.
## Mapped framework controls
### GDPR
- [Art 5.1](../gdpr/art51.md)
## Control questions
Does the organization notify individuals that Personal Data (PD) is collected by sensors?
## Control maturity
|       MATURITY LEVEL       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        DESCRIPTION                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Not performed              | There is no evidence of a capability to notify individuals that Personal Data (PD) is collected by sensors.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Performed internally       | Endpoint Security (END) efforts are ad hoc and inconsistent. CMM Level 1 control maturity would reasonably expect all, or at least most, the following criteria to exist:<br>- Asset management is informally assigned as an additional duty to existing IT/cybersecurity personnel.<br>- IT/cybersecurity personnel use an informal process to design, build and maintain secure configurations for test, development, staging and production environments, including the implementation of appropriate cybersecurity & data privacy controls.<br>- Anti-malware technologies are decentralized but are deployed on all technology assets that can run Anti-malware software. <br>- Data management is decentralized.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Planned and tracked        | Endpoint Security (END) efforts are requirements-driven and formally governed at a local/regional level, but are not consistent across the organization. CMM Level 2 control maturity would reasonably expect all, or at least most, the following criteria to exist:<br>- Endpoint security management is decentralized (e.g., a localized/regionalized function) and uses non-standardized methods to implement secure and compliant practices.<br>- IT/cybersecurity personnel identify cybersecurity & data privacy controls that are appropriate to address applicable statutory, regulatory and contractual requirements for endpoint security management.<br>- Anti-malware technologies are decentralized but are deployed on all technology assets that can run anti-malware software. <br>- Physical controls, administrative processes and technologies focus on protecting High Value Assets (HVAs), including environments where sensitive/regulated data is stored, transmitted and processed.<br>- Technologies are configured to protect data with the strength and integrity commensurate with the classification or sensitivity of the information and mostly conform to industry-recognized standards for hardening (e.g., DISA STIGs, CIS Benchmarks or OEM security guides), including cryptographic protections for sensitive/regulated data.<br>- A Data Protection Impact Assessment (DPIA) is used to help ensure the protection of Personal Data (PD) processed, stored or transmitted on endpoint devices, so that cybersecurity & data privacy controls are implemented in accordance with applicable statutory, regulatory and contractual obligations.<br>- Administrative processes exist and technologies are configured to notify individuals that Personal Data (PD) is collected by sensors.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Well defined               | Endpoint Security (END) efforts are standardized across the organization and centrally managed, where technically feasible, to ensure consistency. CMM Level 3 control maturity would reasonably expect all, or at least most, the following criteria to exist:<br>- Configuration management is centralized for all operating systems, applications, servers and other configurable technologies.<br>- Technologies are configured to protect data with the strength and integrity commensurate with the classification or sensitivity of the information and conform to industry-recognized standards for hardening (e.g., DISA STIGs, CIS Benchmarks or OEM security guides), including test, development, staging and production environments.<br>- Configurations conform to industry-recognized standards for hardening (e.g., DISA STIGs, CIS Benchmarks or OEM security guides) for test, development, staging and production environments.<br>- An Identity & Access Management (IAM) function, or similar function, centrally manages permissions and implements “least privileges” practices for the management of user, group and system accounts, including privileged accounts.<br>- An IT Asset Management (ITAM) function, or similar function, categorizes endpoint devices according to the data the asset stores, transmits and/ or processes and applies the appropriate technology controls to protect the asset and data that conform to industry-recognized standards for hardening (e.g., DISA STIGs, CIS Benchmarks or OEM security guides).<br>- A Security Operations Center (SOC), or similar function, centrally manages anti-malware and anti-phishing technologies, in accordance with industry-recognized practices for Prevention, Detection & Response (PDR) activities.<br>- A Security Incident Event Manager (SIEM), or similar automated tool, is tuned to detect and respond to anomalous behavior that could indicate account compromise or other malicious activities.<br>- The Human Resources (HR) department ensures that every user accessing a system that processes, stores, or transmits sensitive/regulated data is cleared and regularly trained in proper data handling practices. <br>- Unauthorized configuration changes are responded to in accordance with an Incident Response Plan (IRP) to determine if the any unauthorized configuration is malicious in nature.<br>- A Data Protection Impact Assessment (DPIA) is used to help ensure the protection of Personal Data (PD) processed, stored or transmitted on endpoint devices, so that cybersecurity & data privacy controls are implemented in accordance with applicable statutory, regulatory and contractual obligations.<br>- Administrative processes exist and technologies are configured to notify individuals that Personal Data (PD) is collected by sensors. |
| Quantitatively controllled | Endpoint Security (END) efforts are metrics driven and provide sufficient management insight (based on a quantitative understanding of process capabilities) to predict optimal performance, ensure continued operations and identify areas for improvement. In addition to CMM Level 3 criteria, CMM Level 4 control maturity would reasonably expect all, or at least most, the following criteria to exist:<br>- 	Metrics reporting includes quantitative analysis of Key Performance Indicators (KPIs).<br>- 	Metrics reporting includes quantitative analysis of Key Risk Indicators (KRIs).<br>- 	Scope of metrics, KPIs and KRIs covers organization-wide cybersecurity & data privacy controls, including functions performed by third-parties.<br>- 	Organizational leadership maintains a formal process to objectively review and respond to metrics, KPIs and KRIs (e.g., monthly or quarterly review).<br>- 	Based on metrics analysis, process improvement recommendations are submitted for review and are handled in accordance with change control processes.<br>- 	Both business and technical stakeholders are involved in reviewing and approving proposed changes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Continuously improving     | See SP-CMM4. SP-CMM5 is N/A, since a continuously-improving process is not necessary to notify individuals that Personal Data (PD) is collected by sensors.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |