# Network Security Specialist 

This repository contains my work for the **Network Security Specialist** virtual internship.

## Task 2 – Network Traffic Analysis

Analyzed sample network traffic using **Wireshark** and authorized sample capture files.

### Analysis Performed
- Packet and protocol examination
- Source and destination analysis
- TCP and UDP communication analysis
- Protocol hierarchy analysis
- Endpoint and conversation analysis
- Identification of unusual communication patterns

### Tools Used
- Wireshark
- Kali Linux
- Authorized Wireshark sample capture files

**Report:** `Task_2_Network_Traffic_Analysis_Report.docx`

---

## Task 3 – Firewall Rule Analysis

Reviewed firewall access-control concepts and analyzed sample firewall rules to identify:

- Unnecessary open ports and services
- Overly permissive access rules
- Inbound and outbound traffic risks
- Firewall configuration weaknesses
- Recommended security improvements

The firewall configuration used for this analysis was a **constructed educational example**, as no configuration file was provided with the task.

**Report:** `Task_3_Firewall_Rule_Analysis_Report.docx`

---

## Task 4 – Vulnerability Assessment

Performed a basic vulnerability assessment of a **local OWASP Juice Shop laboratory environment**.

**Target:** `127.0.0.1:3000`

### Tools Used
- Nmap
- Nikto
- cURL
- Kali Linux
- Docker

### Assessment Performed
- Port and service discovery
- HTTP security-header review
- HTTP method analysis
- `/robots.txt` review
- `/ftp/` directory exposure analysis
- Manual validation of scanner results
- Identification of security configuration weaknesses
- Risk assessment and remediation recommendations

### Key Observations
- TCP port `3000` was open on the local target.
- `X-Content-Type-Options: nosniff` was present.
- `X-Frame-Options: SAMEORIGIN` was present.
- Content-Security-Policy was not observed in the tested response.
- The `/ftp/` path exposed a directory listing containing multiple files.
- The OPTIONS response advertised several HTTP methods, including `PUT`, `PATCH` and `DELETE`.
- Scanner results were manually checked before being included as findings.

**Report:** `Task_4_Vulnerability_Assessment_Report.docx`

---

## Tools & Technologies

- Kali Linux
- Wireshark
- Nmap
- Nikto
- cURL
- Docker
- GitHub
- OWASP Juice Shop
