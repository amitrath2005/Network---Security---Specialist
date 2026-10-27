# Network Security Specialist

This repository contains my work completed as part of the Network Security Specialist internship with YuvaIntern.

## Task 2 – Network Traffic Analysis

### Objective
Analyze sample network traffic to understand communication patterns and identify potentially suspicious or unusual network activity.

### Tools Used
- Wireshark
- Kali Linux
- Authorized Wireshark sample capture files

### Analysis Performed
- Packet and protocol examination
- Source and destination IP analysis
- Protocol hierarchy analysis
- Endpoint analysis
- TCP/UDP communication analysis
- Identification of unusual communication patterns

### Report
[Task 2 – Network Traffic Analysis Report](./Task_2_Network_Traffic_Analysis_Report.docx)

---

## Task 3 – Firewall Case Study

### Objective
Study firewall concepts, traffic-filtering rules, and access-control practices to understand how firewalls help protect network environments.

### Tools Used
- Firewall rule examples
- Network security documentation
- Firewall access-control concepts

### Analysis Performed
- Reviewed firewall filtering principles
- Prepared illustrative firewall rules
- Examined traffic access and restriction scenarios
- Reviewed network access-control considerations
- Documented security recommendations

### Assessment Note
The firewall rules are educational examples. No actual production firewall configuration was supplied for this task.

### Report
[Task 3 – Firewall Case Study Report](./Task_3_Firewall_Case_Study_Final.docx)

---

## Task 4 – Vulnerability Assessment

### Objective
Assess a controlled web application lab to identify potential security weaknesses and document appropriate mitigation measures.

### Tools Used
- Kali Linux
- OWASP Juice Shop
- Nmap
- Nikto
- cURL

### Analysis Performed
- Assessed the local application at `127.0.0.1:3000`
- Inspected the target service and port
- Reviewed potential web-server security issues
- Examined HTTP response headers
- Checked directory-listing behavior
- Reviewed advertised HTTP methods
- Compared scanner output with direct observations
- Documented findings and remediation recommendations

### Assessment Note
Testing was conducted against the local lab application. Scanner output was not automatically treated as proof of an exploitable vulnerability.

### Report
[Task 4 – Vulnerability Assessment Report](./Task_4_Vulnerability_Assessment_Report.docx)

---

## Task 5 – Security Risk Assessment

### Objective
Assess a representative sample network environment to identify, evaluate, and prioritize security risks based on likelihood and potential impact.

### Work Performed
- Created a sample network architecture
- Documented example IP addresses and network zones
- Developed sample firewall rules for assessment purposes
- Identified six potential security risks
- Evaluated the likelihood and potential impact of each risk
- Assigned risk levels and prioritized the findings
- Recommended security controls and mitigation measures

### Key Risk Areas
- Overly permissive firewall rules
- Guest network access to internal resources
- Broad employee access to database services
- Internet-facing web server exposure
- Insufficient centralized security monitoring
- Dependence on perimeter firewall controls

### Assessment Note
No actual network architecture or firewall configuration was supplied with this task. The architecture and rules were constructed specifically for this educational risk-assessment exercise.

### Report
[Task 5 – Security Risk Assessment Report](./Task_5_Security_Risk_Assessment_Final.docx)

---

## Task 6 – Final Network Security Capstone

### Objective
Research practical network-security practices and perform hands-on checks to understand network configuration, access control, firewall rules, monitoring, logging, and packet-level traffic.

### Tools Used
- Kali Linux
- `ip` and `ss`
- `iptables` and `nftables`
- `tcpdump`
- TShark
- Wireshark
- `getent`

### Practical Work Performed
- Inspected network interfaces and IP addressing
- Reviewed routing information and listening sockets
- Examined existing firewall rules without modifying them
- Checked DNS resolver configuration and hostname resolution
- Reviewed system logs, uptime, and memory usage
- Captured a limited sample of network traffic using tcpdump
- Saved a PCAP capture file
- Analyzed packet protocols using TShark
- Verified the PCAP file format, ownership, and permissions
- Documented findings, limitations, and recommendations

### Key Areas Examined
- Network configuration and routing
- Firewall and Docker networking rules
- DNS resolution and system logging
- TCP, TLS, UDP, and DNS traffic in the captured sample
- Packet-capture handling and access permissions
- Network segmentation and least-privilege principles
- Secure configuration, monitoring, and logging

### Assessment Note
The observations represent the local Kali Linux lab environment, not BSP's internal network. The packet sample did not establish malicious activity. The attempted PCAP permission change was unsuccessful and was documented accordingly.

### Report
[Task 6 – Final Network Security Capstone Report](./Task_6_Network_Security_Capstone_Final_Report.docx)

---

## Skills and Technologies

- Network traffic analysis
- Packet inspection and protocol analysis
- Firewall rule review
- Vulnerability assessment in a controlled lab
- Security risk assessment
- Network configuration inspection
- DNS troubleshooting
- Packet capture and analysis
- Security documentation and reporting
- Network security best practices

---

## Disclaimer

This repository contains internship reports, controlled lab exercises, and educational examples. Constructed network architectures and sample firewall rules are identified as illustrative. The practical work does not represent a security assessment of BSP's production network or any other organization's internal infrastructure.
