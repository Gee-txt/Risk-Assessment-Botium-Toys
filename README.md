# Risk-Assessment-Botium-Toys
Conduct an internal security audit 
# Botium Toys Security Audit

This project is part of my cybersecurity portfolio and was completed as part of Google's Cybersecurity Professional Certificate (Play It Safe: Manage Security Risks course). It involves a mock security audit of a fictional company, Botium Toys, to identify potential risks, threats, and vulnerabilities, and offer mitigation strategies in line with industry best practices.

## Table of Contents
1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Internal Security Audit Workflow](#internal-security-audit-workflow)
4. [Controls Assessment](#controls-assessment)
5. [Compliance Checklist](#compliance-checklist)
6. [Stakeholder Memorandum](#stakeholder-memorandum)
7. [Conclusion](#conclusion)

## Introduction
This document outlines the internal security audit assessment done for Botium Toys, including the audit workflow, controls assessment, compliance checklist, and recommendations for improving the company's cybersecurity posture.

## Scenario
Botium Toys is a small U.S. business that develops and sells toys. With its growing online presence, the IT department is under pressure to ensure business continuity and compliance with international data security regulations (GDPR, PCI DSS). This audit focuses on improving their cybersecurity framework and ensuring regulatory compliance.

## Internal Security Audit Workflow
The audit was carried out in two main phases:
1. **Audit Planning and Execution**: We analyzed the company's current security controls, identified risks, and assessed the compliance requirements.
2. **Reporting and Recommendations**: Findings were summarized and communicated to stakeholders, along with actionable recommendations for addressing the identified vulnerabilities.

## Controls Assessment
### Current Assets
Botium Toys manages several critical assets, including:
- On-premises and employee devices
- Vendor access and data center hosting services
- Legacy system maintenance requiring manual intervention

### Administrative Controls
| Control Name                | Type                       | Needs Implementation | Priority  |
|-----------------------------|----------------------------|----------------------|-----------|
| Least Privilege              | Preventative               | Yes                  | High      |
| Disaster Recovery Plans      | Corrective                 | Yes                  | High      |
| Password Policies            | Preventative               | Yes                  | High      |
| Access Control Policies      | Preventative               | Yes                  | High      |
| Account Management Policies  | Preventative               | Yes                  | High      |
| Separation of Duties         | Preventative               | Yes                  | High      |

### Technical and Physical Controls
| Control Name                     | Type                        | Needs Implementation | Priority  |
|-----------------------------------|-----------------------------|----------------------|-----------|
| Firewall                          | Preventative                | No                   | N/A       |
| Intrusion Detection System (IDS)  | Detective                   | Yes                  | High      |
| Encryption                        | Deterrent                   | Yes                  | High      |
| Backups                           | Corrective                  | Yes                  | High      |
| Antivirus (AV) Software           | Corrective                  | Yes                  | High      |
| Closed-Circuit TV (CCTV)          | Preventative/Detective      | Yes                  | High/Med  |
| Locks and Locking Cabinets        | Preventative                | Yes                  | High      |

## Compliance Checklist
The following standards were considered for compliance:
- **General Data Protection Regulation (GDPR)**: Ensures data privacy for E.U. citizens.
- **Payment Card Industry Data Security Standard (PCI DSS)**: Protects credit card information from being compromised.
- **System and Organization Controls (SOC 1 & SOC 2)**: Evaluates data privacy, user access policies, and overall system security.

## Stakeholder Memorandum
### Key Findings:
- Lack of a disaster recovery plan and insufficient controls for user account management and physical security.
- Missing technical controls like encryption and IDS.
- Non-compliance with key regulations (GDPR, PCI DSS).

### Recommendations:
- Implement the principle of least privilege and ensure proper access control policies.
- Deploy intrusion detection systems, encryption, and backup solutions to protect sensitive data and maintain business continuity.
- Ensure compliance with GDPR and PCI DSS by implementing data protection policies and reporting mechanisms.

## Conclusion
This internal audit revealed significant gaps in Botium Toys' security posture. By implementing the recommended controls and addressing compliance issues, the company can significantly improve its security and regulatory standing. I enjoyed working on this mock audit and applying the principles learned in my cybersecurity studies.

---

Feel free to explore the [Audit Report](./Documentation/Audit-Scope-and-Goals.pdf) for a more detailed review of the findings and recommendations.

---
