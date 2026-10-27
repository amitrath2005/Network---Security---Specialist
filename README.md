Task 2 – Network Traffic Analysis

Analyzed sample network traffic to understand communication patterns, protocols, and packet-level behavior using Wireshark.

Work Performed

- Examined sample packet captures in Wireshark.
- Reviewed network protocols and packet details.
- Observed traffic patterns and communication behavior.
- Documented findings and security observations.

Report: "View Task 2 – Network Traffic Analysis Report" (./Task_2_Network_Traffic_Analysis_Report.docx)

Task 3 – Firewall Case Study

Prepared a firewall case study covering traffic filtering, example firewall rules, and network access-control considerations.

Work Performed

- Reviewed firewall concepts and filtering behavior.
- Prepared illustrative firewall rules.
- Examined access-control principles and security implications.
- Documented recommendations for improving firewall security.

Assessment Note: The firewall rules are educational examples, not a verified configuration from a real production network.

Report: "View Task 3 – Firewall Case Study Report" (./Task_3_Firewall_Case_Study_Final.docx)

Task 4 – Vulnerability Assessment

Performed a controlled vulnerability-assessment exercise using OWASP Juice Shop hosted locally in a lab environment.

Work Performed

- Tested the local application at "127.0.0.1:3000".
- Used Nmap to inspect the target service.
- Used Nikto to review potential web-server security issues.
- Used cURL to inspect HTTP responses and headers.
- Reviewed directory-listing exposure and HTTP method configuration.
- Compared scanner output with direct observations where possible.
- Documented findings and remediation recommendations.

Key Areas Examined

- Web directory-listing exposure.
- HTTP methods and configuration.
- Security-related HTTP response headers.
- Verification of scanner findings.

Assessment Note: Testing was conducted against the local lab application. Scanner findings were not automatically treated as confirmed vulnerabilities.

Report: "View Task 4 – Vulnerability Assessment Report" (./Task_4_Vulnerability_Assessment_Report.docx)

Task 5 – Security Risk Assessment

Prepared a risk assessment of a representative sample network environment to identify, evaluate, and prioritize risks based on likelihood and potential impact.

Work Performed

- Created a sample network architecture.
- Documented example IP addresses and network zones.
- Developed sample firewall rules for assessment purposes.
- Identified six potential security risks.
- Evaluated the likelihood and potential impact of each risk.
- Assigned risk levels and prioritized the findings.
- Recommended security controls and mitigation measures.

Key Risk Areas

- Overly permissive firewall rules.
- Guest network access to internal resources.
- Broad employee access to database services.
- Internet-facing web server exposure.
- Insufficient centralized security monitoring.
- Dependence on perimeter firewall controls.

Assessment Note: No actual network architecture or firewall configuration was supplied with this task. The architecture and rules were constructed specifically for this educational risk-assessment exercise.

Report: "View Task 5 – Security Risk Assessment Report" (./Task_5_Security_Risk_Assessment_Final.docx)

Task 6 – Final Network Security Capstone

Documented practical network-security practices and performed hands-on checks in a local Kali Linux environment.

Work Performed

- Inspected network interfaces, IP addressing, and routing information.
- Reviewed listening sockets and system resources.
- Examined existing iptables and nftables rules without modifying them.
- Checked DNS configuration and hostname resolution.
- Reviewed system logs and resource usage.
- Verified the availability of Nmap, Wireshark, TShark, and tcpdump.
- Captured network traffic using tcpdump.
- Saved and analyzed a PCAP file using TShark.
- Verified the capture file format, ownership, and permissions.
- Documented findings and security recommendations.

Key Areas Examined

- Network configuration and routing.
- Firewall and Docker networking rules.
- DNS resolution and system logging.
- TCP, TLS, UDP, and DNS traffic.
- Packet-capture handling and access permissions.
- Network segmentation, least privilege, monitoring, and secure configuration.

Assessment Note: The findings describe the local Kali Linux lab environment, not BSP's internal network. The packet sample did not establish malicious activity.

Report: "View Task 6 – Final Network Security Capstone Report" (./Task_6_Network_Security_Capstone_Final_Report.docx)
