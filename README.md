# Network-Attack-Analysis-&-PCAP-Investigation

A project focused on attack analysis, packet investigation, incident response, and defensive security controls.

Overview

This project combines theory and practical network forensics to investigate a real attack scenario captured in a PCAP file.

The work covers:

Man-in-the-Middle (MITM) attack analysis
Wireshark packet investigation
Apache Tomcat compromise analysis
Indicators of Compromise (IOCs)
MITRE ATT&CK mapping
IDS/IPS detection strategies
Snort rule development
Incident reporting and response
Project Structure
Part 1 – Man-in-the-Middle Attack

A technical breakdown of how a MITM attack works, including:

ARP Spoofing
Traffic interception
Session hijacking
SSL/TLS downgrade techniques
Data manipulation and credential theft

The analysis explains the protocols, OSI layers, attack prerequisites, and business impact.

Part 2 – PCAP Analysis (Tomcat Takeover)

Using Wireshark, I investigated a compromised Apache Tomcat server and reconstructed the attack chain.

Key findings:

External reconnaissance and port scanning
Discovery of exposed Tomcat services
Directory enumeration using Gobuster
Upload of a malicious .war file
Reverse shell deployment
Command & Control activity
Possible lateral movement inside the network

Tools used:

Wireshark
TCP Stream Analysis
Protocol Hierarchy
Conversation Statistics
Custom display filters
Part 3 – IDS/IPS Defensive Controls

The project discusses how intrusion detection systems can identify MITM activity and other malicious behavior.

Topics include:

NIDS vs HIDS
Network anomaly detection
ARP spoofing detection
SSL stripping indicators
Custom Snort rules
Part 4 – Security Fundamentals

Short discussions covering:

Why WEP is obsolete
WPA2/WPA3 security improvements
GDPR breach reporting requirements
NIST security controls
Part 5 – Incident Report

A management-oriented incident report summarizing:

What happened
Affected systems
Severity assessment
Recommended remediation actions
Lessons learned
Skills Demonstrated
Network Security
Packet Analysis
Wireshark
Threat Hunting
Incident Response
Digital Forensics
IDS/IPS Concepts
Snort Rule Writing
MITRE ATT&CK
Risk Assessment
Technical Reporting
Key Takeaway

This project demonstrates how a real-world intrusion can be identified and reconstructed from network traffic, moving from reconnaissance and exploitation to persistence and command-and-control activity, while also exploring practical detection and mitigation techniques.
