# Network Security Improvement Plan (NIST CSF 2.0 Aligned)

## Description

This repository contains a comprehensive **Post-Incident Analysis and Strategic Hardening Plan** designed for a multimedia and web design organization. Following a recent Denial of Service (DoS) attack—in which an unconfigured perimeter firewall allowed an uncontrolled flood of ICMP packets to disrupt internal network operations for two hours—this project outlines a robust, multi-layered cybersecurity remediation strategy.

The plan is mapped directly to the **National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF 2.0)**. It incorporates the newly introduced **Govern (GV)** core function alongside **Identify (ID)**, **Protect (PR)**, **Detect (DE)**, **Respond (RS)**, and **Recover (RC)** to ensure complete organizational resilience across all digital media and web hosting services.

## NIST CSF 2.0 Framework Alignment

1. **Govern (GV):** Establishing enterprise-wide cybersecurity governance, defining clear administrative roles and responsibilities, and integrating risk management into multimedia service operations.
2. **Identify (ID):** Deploying comprehensive network mapping, maintaining real-time asset inventories, and scheduling recurring firewall configuration audits to prevent unconfigured deployments.
3. **Protect (PR):** Enforcing strict deny-by-default firewall rules, ICMP rate-limiting, source IP address verification (anti-spoofing), and network segmentation.
4. **Detect (DE):** Utilizing continuous network monitoring tools (NetFlow/SIEM), automated alerting thresholds, and IDS/IPS traffic filtering to catch anomalies early.
5. **Respond (RS):** Formalizing a dedicated DoS incident response playbook, rapid containment procedures, and root cause analysis workflows.
6. **Recover (RC):** Implementing structured phased service restoration protocols, 48-hour post-incident debriefs, and updated Business Continuity / Disaster Recovery (BC/DR) plans.

## Incident Summary & Mapping

| CSF Function | Identified Vulnerability / Gap | Corrective Action & Strategic Improvement | 
| :--- | :--- | :--- | 
| **Govern (GV)** | Lack of centralized oversight for firewall deployment and baseline security policy compliance. | Establish governance policies, define clear roles, and integrate risk management into multimedia service operations. | 
| **Identify (ID)** | Unconfigured firewall left exposed to unauthorized external traffic. | Implement comprehensive asset mapping, regular configuration audits, and risk categorization. | 
| **Protect (PR)** | Unrestricted ingress for ICMP flood packets and lack of anti-spoofing controls. | Enforce deny-by-default rules, ICMP rate-limiting, source IP verification, and network segmentation. | 
| **Detect (DE)** | Delayed detection of abnormal bandwidth spikes and flood patterns. | Deploy continuous network monitoring software (NetFlow/SIEM), alerting mechanisms, and IDS/IPS filtering. | 
| **Respond (RS)** | Ad-hoc incident response during the 2-hour outage without a dedicated DoS playbook. | Formalize a DoS incident response playbook, rapid containment procedures, and root cause analysis workflows. | 
| **Recover (RC)** | Absence of structured restoration phasing and formal post-incident review cycles. | Establish phased service restoration protocols, 48-hour debriefs, and updated BC/DR continuity plans. | 

## Repository Contents

* `network_security_improvement_plan_nist_csf_2.0.docx`: The complete, professionally formatted Word document containing the detailed plan and executive summary.
* `README.md`: Project documentation and repository guide.

## Usage & Contribution

This documentation serves as an internal operational standard and security policy reference for network administrators, cybersecurity analysts, and IT leadership. For updates, suggestions, or contributions, please open an issue or submit a pull request.