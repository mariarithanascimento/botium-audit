# Conducting a Security Audit: Botium Toys

> Hello!! Welcome to the case study "Conducting a Security Audit: Botium Toys." Here, you will find a brief explanation of the Control Categories, the company's scope, and finally, the checklist.

## Summary
- [Control Categories](#control-categories)
- [Botium Toys: Scope Report, Objectives, and Risk Assessment](#botium-toys---scope-report-objectives-and-risk-assessment)
- [Controls and compliance checklist (pdf)]()

## `Control Categories`

Cybersecurity controls are grouped into three main categories:

 - Administrative/Managerial Controls  
 - Technical Controls  
 - Physical/Operational Controls

**Administrative/Managerial Controls** address the human component of cybersecurity. These controls include policies and procedures that define how an organization manages data and clarify employee responsibilities, including their role in protecting the organization. While administrative controls are often policy-based, implementing these policies may require the use of technical or physical controls.  
**Technical Controls** consist of solutions such as firewalls, intrusion detection systems (IDS), intrusion prevention systems (IPS), antivirus (AV) products, encryption, etc. Technical controls can be used in various ways to meet organizational objectives.  
**Physical/Operational Controls** include door locks, cabinet locks, surveillance cameras, badge readers, etc. They are used to limit physical access to physical assets by unauthorized personnel.

### Types of Control
Control types include, but are not limited to:

 - Preventive
 - Corrective
 - Detective
 - Deterrent

These controls work together to provide a defense in depth and protect assets. *Preventive controls* are designed to prevent an incident from occurring. *Corrective controls* are used to restore an asset after an incident. *Detective controls* are implemented to determine if an incident has occurred or is ongoing. *Deterrent controls* are designed to discourage attacks.

### Administrative/Managerial Controls
|Control Name| Control Type |Purpose of the Control |
|------------------------------------|--|--|
|Principle of Least Privilege | Preventive | Reduces the risk and overall impact of malicious insiders or compromised accounts.                                 
|Disaster Recovery Plans | Corrective | Provides business continuity.  
|Password Policies | Preventive | Reduces the likelihood of account compromise by brute force or dictionary attack techniques.  
|Access Control Policies | Preventive | Strengthens confidentiality and integrity by defining which groups can access or modify data.  
|Account Management Policies | Preventive | Manages account lifecycle, reducing the attack surface and limiting the overall impact of disgruntled former employees and default account usage.  
|Separation of Duties | Preventive | Reduces the risk and overall impact of malicious insiders or compromised accounts.

### Technical Controls

|Control Name | Control Type | Purpose of the Control |
|--------------------------------------------------------|--|--|
| Firewall | Preventive | Filters unwanted or malicious traffic from entering the network.
IDS/IPS | Detective | Detects and prevents anomalous traffic matching a signature or rule.  
Encryption | Deterrent | Provides confidentiality for sensitive information.  
Backups | Corrective | Restores/recover from an event.  
Password Management | Preventive | Reduces password fatigue.  
Antivirus Software (AV) | Preventive | Scans to detect and quarantine known threats.  
Monitoring, Maintenance, and Manual Intervention | Preventive | Necessary to identify and manage threats, risks, or vulnerabilities in outdated systems.

### Physical/Operational Controls
| Control Name |  Control Type | Purpose of the Control |
|--|--|--|
|Time-controlled safe | Deterrent | Reduces attack surface and overall impact of physical threats.  
Adequate Lighting | Deterrent | Deters threats by limiting "hiding" locations.  
Closed-Circuit Television (CCTV) | Preventive/Detective | CCTV is both a preventive and detective control as its presence can reduce the risk of certain events occurring and can be used post-event to inform about the event conditions.  
Locked Cabinets (for network equipment) | Preventive | Strengthens integrity by preventing unauthorized personnel and others from physically accessing or modifying network infrastructure equipment.  
Signage Indicating the Alarm Service Provider | Deterrent | Deters certain types of threats by making the probability of a successful attack appear low.  
Locks | Deterrent/Preventive | Strengthens integrity by deterring and preventing unauthorized personnel from physically accessing assets.  
Fire Detection and Prevention (fire alarm, sprinkler system, etc.) | Detective/Preventive | Detects fire at the physical location and prevents damage to physical assets like inventory, servers, etc.

## `Botium Toys - Scope Report, Objectives, and Risk Assessment`

**1. Audit scope and objectives.**  
**Scope:** The scope of this audit covers the entire security program of Botium Toys. This includes its assets, such as employee equipment and devices, the internal network, and systems. It will be necessary to review Botium Toys' assets, as well as the controls and compliance practices in place.  
**Objectives:** Assess the existing assets and complete the controls and compliance checklist to determine which controls and best compliance practices need to be implemented to improve Botium Toys' security posture.

**2. Current assets**  
The assets managed by the IT Department include:

 - On-site equipment for business needs in the office.  
 - Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.  
 - Products available for retail sale on-site and online, stored in the company's adjacent warehouse.  
 - Management of systems, software, and services: accounting, telecommunications, database, security, e-commerce, and inventory management.  
 - Internet access  
 - Internal network  
 - Data retention and storage  
 - Maintenance of legacy systems: end-of-life systems requiring human monitoring.

**3. Risk assessment**  
**Risk Description**  
There is currently inadequate asset management. Additionally, *Botium Toys* does not have all appropriate controls in place and may not fully comply with U.S. and international regulations and standards.  
**Best Control Practices**  
The first of the five NIST CSF functions is Identify. Botium Toys will need to allocate resources to identify assets so they can be properly managed. Additionally, existing assets will need to be classified, and the impact of losing these assets, including systems, on business continuity will need to be determined.  
**Risk Score**  
On a scale of 1 to 10, the risk score is 8, which is quite high. This is due to the lack of controls and adherence to best compliance practices.

**4. Additional comments**  
The potential impact of asset loss is classified as medium, as the IT department does not know which assets would be at risk. The risk to assets or fines from regulatory bodies is high because Botium Toys does not have all necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following points for specific details:

- Currently, all Botium Toys employees have access to internally stored data and can access cardholder data and customers' personally identifiable information (PII/SPII).  
- Encryption is not currently used to ensure the confidentiality of customers' credit card information, which is accepted, processed, transmitted, and stored locally in the company's internal database.  
- Access controls related to the principle of least privilege and separation of duties have not been implemented.  
- The IT department has ensured availability and integrated controls to ensure data integrity.  
- The IT department has a firewall that blocks traffic based on a properly defined set of security rules.  
- Antivirus software is installed and regularly monitored by the IT department.  
- The IT department has not installed an intrusion detection system (IDS).  
- There are currently no disaster recovery plans in place, and the company does not have backups of critical data.  
- The IT department has established a plan to notify EU customers within 72 hours in the event of a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members and other employees to document and maintain data properly.  
- While there is a password policy, its requirements are minimal and do not comply with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number, special characters).  
- There is no centralized password management system to enforce the minimum password policy requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to retrieve or reset a password.  
- Although legacy systems are monitored and maintained, there is no regular schedule for these tasks, and intervention methods are unclear.  
- The physical location of the store, which includes Botium Toys' main offices, the store, and the product warehouse, has sufficient locks, updated closed-circuit television (CCTV) surveillance systems, as well as working fire detection and prevention systems.
