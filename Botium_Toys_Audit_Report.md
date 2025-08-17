# **Security Audit of Botium Toys: Recommendations Report for the IT Manager**

### **Project Overview**

This document is part of a larger security auditing project for a fictional company, Botium Toys. The project involved performing a comprehensive security audit to assess the company's current security posture, identify vulnerabilities, and provide prioritized recommendations for improvement. This report summarizes the key findings of that audit, outlines the risks associated with the identified vulnerabilities, and presents a phased plan for implementing necessary controls to enhance Botium Toys' overall security.

### **Existing Security Strengths**

While the audit identified several areas for improvement, it is important to acknowledge the existing controls that are functioning well at Botium Toys. These controls provide a foundation upon which to build a stronger security program.

* **Network Security:** A firewall is in place to block unwanted or malicious traffic.  
* **Endpoint Protection:** Antivirus software is installed and regularly monitored by the IT department.  
* **Physical Security:** The physical location is well-protected with sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, and functioning fire detection and prevention systems.

### **Key Findings and Risk Areas**

Based on our assessment, the following are the most critical areas of concern, which have led to an overall risk score of **8 out of 10**:

* **Inadequate Access Control:** All employees currently have access to Personally Identifiable Information (PII) and Sensitive Personally Identifiable Information (SPII), which violates the principle of **least privilege**. This increases the risk of both accidental data exposure and malicious insider threats.  
* **Absence of Core Controls:** Botium Toys lacks several foundational security controls, including **disaster recovery plans**, **backups of critical data**, and an **intrusion detection system (IDS)**. This leaves the company unprepared for major security incidents and system failures.  
* **Weak Password Management:** The current password policy is not enforced, and there is no centralized password management system. This increases the likelihood of password compromise.  
* **Compliance Gaps:** Botium Toys is not fully compliant with the **Payment Card Industry Data Security Standard (PCI DSS)**, the **General Data Protection Regulation (GDPR)**, and **System and Organizations Controls (SOC 1 & 2\)**. These compliance failures expose the company to legal and financial penalties.

### **Risk Prioritization**

The following table provides a quick summary of the identified risks, their potential impact, and their recommended priority for mitigation.

| Risk Area | Likelihood | Impact | Priority |
| :---- | :---- | :---- | :---- |
| Inadequate Access Control | High | High | Critical |
| Absence of Core Controls | High | High | Critical |
| Weak Password Management | Medium | High | High |
| Compliance Gaps | High | High | Critical |

### **Summary of Recommendations**

We recommend a phased approach to implementing controls, starting with the highest-priority items that directly address the most significant risks.  
**Phase 1: Immediate Actions (Administrative & Managerial Controls \- 0-3 Months)**  
These controls are the top priority as they directly address the human element and administrative gaps.

* **Establish Least Privilege:** Implement a policy to ensure employees only have access to the data necessary for their specific job functions. This will significantly reduce the attack surface.  
* **Implement Separation of Duties:** Define clear roles and responsibilities to prevent a single employee from having too much control over sensitive processes, reducing the risk of fraud or error.  
* **Adopt Secure Password Policies:** Create and enforce a strong password policy that requires complexity and regular changes.  
* **Establish Backups and Disaster Recovery Plans:** Immediately create a regular schedule for backing up all critical data and develop a comprehensive disaster recovery plan to ensure business continuity in the event of a major incident.

**Phase 2: Short-Term Actions (Technical Controls \- 3-6 Months)**  
Once the foundational administrative controls are in place, focus on these technical implementations.

* **Implement an Intrusion Detection System (IDS):** An IDS will provide a crucial layer of defense by detecting and alerting on malicious or anomalous network activity.  
* **Deploy a Centralized Password Management System:** This system will enforce password policies, reduce password fatigue for employees, and improve overall security.  
* **Implement Encryption:** Encrypt sensitive customer data, especially credit card information, both in transit and at rest, to ensure confidentiality and meet compliance requirements.

**Phase 3: Ongoing & Long-Term Actions (Operational & Ongoing Controls \- 6+ Months)**  
This phase addresses the organization’s long-term maintenance and monitoring needs.

* **Implement Manual Monitoring, Maintenance, and Intervention for Legacy Systems:** Establish a regular schedule for these tasks to ensure end-of-life systems are not vulnerable to new threats.

By implementing these recommendations, Botium Toys can significantly improve its security posture, reduce its overall risk score, and move toward full compliance with industry standards and regulations, including **PCI DSS, GDPR, and SOC 1 & 2**.