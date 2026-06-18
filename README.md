# Network Attack Analysis & PCAP Investigation

A cybersecurity case study focused on network attack analysis, packet investigation, incident response, and defensive security controls.


## Overview

This project combines theoretical research with practical network forensics to investigate a real attack scenario using packet capture (PCAP) analysis.

The work covers:

- Man-in-the-Middle (MITM) attacks
- Wireshark packet analysis
- Apache Tomcat compromise investigation
- Indicators of Compromise (IOCs)
- MITRE ATT&CK mapping
- IDS/IPS detection methods
- Snort rule creation
- Incident response and reporting

The objective was not only to identify what happened during the attack, but also to understand how it happened, what weaknesses were exploited, how the compromise could have been detected earlier, and how similar incidents can be prevented in the future.


## Project Breakdown

### Part 1 – Man-in-the-Middle Attack Analysis

A technical examination of a MITM attack, including:

- ARP Spoofing
- Traffic interception
- Session hijacking
- SSL/TLS downgrade attacks
- Data manipulation
- Credential theft

The analysis explains attack prerequisites, exploited vulnerabilities, protocols involved, OSI layers, and potential business impact.

### Part 2 – PCAP Investigation (Tomcat Takeover)

Using Wireshark, I reconstructed a full attack chain against an Apache Tomcat server.

Key findings include:

- External reconnaissance
- Port scanning activity
- Directory enumeration using Gobuster
- Discovery of exposed Tomcat services
- Upload of a malicious `.war` file
- Reverse shell deployment
- Command-and-Control communication
- Potential lateral movement

Tools and techniques used:

- Wireshark
- TCP Stream Analysis
- Protocol Hierarchy
- Conversation Statistics
- Custom display filters
- IOC identification

### Part 3 – IDS/IPS Detection Strategy

This section explores how defensive monitoring systems could detect and respond to the attack.

Topics covered:

- Network IDS (NIDS) vs Host IDS (HIDS)
- Detection of ARP spoofing
- SSL stripping indicators
- Traffic anomaly detection
- Custom Snort rules
- Additional security controls


### Part 4 – Security Fundamentals

Short discussions covering:

- Why WEP is considered insecure
- WPA2 and WPA3 improvements
- GDPR breach reporting requirements
- NIST security controls

### Part 5 – Incident Report

A management-focused incident report summarizing:

- What happened
- Timeline of events
- Affected systems
- Severity assessment
- Recommended actions
- Lessons learned

## Skills Demonstrated

- Network Security
- Packet Analysis
- Wireshark
- Digital Forensics
- Threat Hunting
- Incident Response
- MITRE ATT&CK
- IDS/IPS Concepts
- Snort Rule Development
- Risk Assessment
- Technical Reporting

## Attack Timeline Summary

1. External attacker performs reconnaissance.
2. Open Tomcat service discovered on port 8080.
3. Automated directory enumeration identifies exposed resources.
4. Administrative interface is accessed.
5. Malicious `.war` file uploaded.
6. Reverse shell established.
7. Persistent access achieved.
8. Outbound Command-and-Control communication observed.
9. Possible lateral movement inside the network.


## Key Takeaways

This project demonstrates how packet captures can be used to reconstruct an attack from initial reconnaissance to full compromise.

The investigation highlights the importance of:

- Network visibility
- Early threat detection
- Secure service configuration
- Continuous monitoring
- Incident response preparedness



All analysis was performed using training material, lab environments, and publicly available cybersecurity resources. No real systems were targeted or accessed during this project.
