# Cybersecurity Portfolio - Ahmad Jacob Williams

## About Me
I am an entry-level cybersecurity professional with hands-on experience in threat investigation, log analysis, and incident response. Completed the Google Cybersecurity Certificate and lab projects, demonstrating practical skills to help organizations detect, analyze, and mitigate cyber threats. Passionate about protecting systems and continuously developing skills to contribute effectively across security operations.

## Certifications
- Google Cybersecurity Certificate (Verification: https://www.credly.com/badges/9952b36a-c246-4d56-b4d3-b1463b4b0792/public_url)
- CompTIA Security+ (In Progress)

## Technical Skills
- Frameworks: NIST CSF, NIST SP 800-30
- Tools: Wireshark, VirusTotal
- Languages: Python, SQL
- Systems: Linux
- Concepts: Incident Response, Risk Assessment, Access Control, Log Analysis

## Projects

### Controls and Compliance Assessment – Botium Toys

**Scenario Summary:**  
Botium Toys is a fictional U.S. toy company expanding its online presence internationally. Using the IT manager’s Scope, Goals, and Risk Assessment Report and the Control Categories Document, I performed an internal audit to assess controls, compliance, and potential security risks, including PCI DSS and GDPR adherence.

**My Role / Skills Demonstrated:**  
- Reviewed the IT manager’s scope, goals, and risk assessment  
- Completed a controls and compliance checklist for technical and organizational safeguards  
- Evaluated compliance with PCI DSS, GDPR, and SOC type 1 & 2 frameworks  
- Provided actionable recommendations to mitigate risks and improve security posture
 
**Key Highlights / Findings:**  
- Identified gaps in least privilege and separation of duties  
- Recommended encryption for sensitive customer data  
- Suggested implementing Intrusion Detection System (IDS) and Disaster Recovery Plan  
- Proposed stronger password policies and multi-factor authentication  
- Developed a plan for monitoring and maintaining legacy systems
  
**Supporting Documents:**
- [Scope, Goals, and Risk Assessment Report (PDF)](Botium-Toys-Scope-goals-risk-assessment-report.pdf)
- [Control Categories Document (PDF)](Control-categories.pdf)
- [Controls and Compliance Checklist (PDF)](Security-Audit-Controls-and-compliance-checklist.pdf)

  ---

### Incident Response Using NIST Cybersecurity Framework – DDOS Attack

**Scenario Summary:**
The organization, a multimedia company providing web design, graphic design, and social media marketing services to small businesses, experienced a DDOS (Distributed Denial of Service) attack that compromised the internal network for two hours. The attack involved a flood of ICMP (Internet Control Message Protocol) pings entering through an unconfigured firewall, causing internal network services to stop responding. The cybersecurity team investigated the incident and implemented mitigation steps to restore critical services.

**My Role / Skills Demonstrated:**  
- Applied the NIST Cybersecurity Framework to analyze and respond to the incident  
- Identified the type and scope of the ICMP flood attack  
- Recommended network hardening techniques, firewall rules, and IDS/IPS deployment  
- Developed procedures for monitoring, detection, and recovery  
- Produced an incident report with actionable recommendations for preventing future attacks

**Key Highlights / Findings:**  
- Determined the attack type: ICMP flood DDOS  
- Implemented firewall rules to limit incoming ICMP packets  
- Configured IDS/IPS to detect and filter suspicious traffic  
- Applied source IP verification and log analysis to detect abnormal patterns  
- Planned recovery steps to restore critical network services and prevent future attacks  

**Supporting Documents:**  
- [Incident Report Analysis (PDF)](Incident-Report-Analysis.pdf)

---

### Linux File Permission Management – Access Control Hardening

**Scenario Summary:**  
In a simulated enterprise environment, I worked as a security professional supporting a research team at a large organization. My task was to review and modify Linux file and directory permissions within the `projects` directory to ensure users had appropriate authorization and to remove unauthorized access.

**My Role / Skills Demonstrated:**  
- Used `ls -la` to audit file and directory permissions, including hidden files  
- Analyzed 10-character Linux permission strings to determine user, group, and other access levels  
- Applied the principle of least privilege to remove unauthorized write and execute permissions  
- Used `chmod` to modify file and directory permissions appropriately  
- Verified changes through command-line validation  

**Key Technical Actions Performed:**  
- Identified permission misconfigurations in project files  
- Removed write access for “other” users where unauthorized  
- Modified permissions on hidden archived files (e.g., `.project_x.txt`)  
- Restricted execute access on the `drafts` directory to a single authorized user (`researcher2`)  
- Ensured proper separation of access between user, group, and other  

**Commands Used:**  
- `ls -la`  
- `chmod`  
- Permission modifiers such as `u-w`, `g-w`, `g+r`, and removal of group execute permissions  

**Security Concepts Applied:**  
- Least Privilege  
- Access Control  
- Authorization Management  
- File System Hardening  

**Supporting Documents:**  
- [Linux File Permissions Report (PDF)](File-Permissions-In-Linux.pdf)
- [Current File Permissions (PDF)](Current-File-Permissions.pdf)

---

### SQL Query Filtering – Security Investigation & Log Analysis

**Scenario Summary:**  
In a simulated enterprise environment, I worked as a security professional investigating potential security issues involving login attempts and employee machines. Using SQL, I analyzed data from the `log_in_attempts` and `employees` tables to identify suspicious activity, policy violations, and systems requiring security updates.

**My Role / Skills Demonstrated:**  
- Queried relational databases using SQL  
- Applied filtering techniques using WHERE, AND, OR, and NOT operators  
- Used pattern matching with LIKE and wildcard %  
- Investigated failed login attempts and abnormal geographic access  
- Retrieved employee machine data for targeted security updates  
- Interpreted query results to support security decision-making  

**Key Technical Actions Performed:**  
- Retrieved 19 failed login attempts that occurred after 18:00 (after-hours activity)  
- Identified 75 login attempts occurring on specific dates (2022-05-08 and 2022-05-09)  
- Filtered login attempts originating outside of Mexico using pattern matching (NOT LIKE 'MEX%')  
- Retrieved employees in the Marketing department located in the East building  
- Filtered employees in the Finance or Sales departments for targeted security updates  
- Retrieved all employees not in the Information Technology department for additional system updates  

**SQL Concepts Applied:**  
- SELECT statements with wildcard (*)  
- WHERE clause filtering  
- Logical operators: AND, OR, NOT  
- Comparison operators (>)  
- Pattern matching using LIKE and % wildcard  
- Multi-condition filtering for investigative analysis  

**Security Concepts Applied:**  
- Log Analysis  
- Threat Detection  
- Anomalous Login Investigation  
- Access Monitoring  
- Department-Based Asset Management  
- Security Data Analysis  

**Supporting Documents:**  
- [SQL Filters Investigation Report (PDF)](Apply-Filters-To-SQL-Queries.pdf)

---

### Vulnerability Assessment – Publicly Accessible Database Server

**Scenario Summary:**  
In a simulated enterprise environment involving an e-commerce company, I conducted a vulnerability assessment of a remote MySQL database server that had been publicly accessible for three years. The server stores valuable business data used by remote employees worldwide to identify potential customers. Using NIST SP 800-30 Rev. 1 as guidance, I evaluated risks associated with public exposure and its impact on business operations.

**My Role / Skills Demonstrated:**  
- Conducted a vulnerability assessment of a publicly exposed database server  
- Applied NIST SP 800-30 Rev. 1 risk analysis methodology  
- Evaluated threat sources, likelihood, severity, and calculated overall risk  
- Assessed business impact related to confidentiality, integrity, and availability  
- Developed remediation strategies to reduce organizational risk  

**Risk Analysis (NIST SP 800-30 Methodology):**

- **Hacker Reconnaissance**  
  - Likelihood: 3 (High)  
  - Severity: 2 (Moderate)  
  - Risk Score: 6  

- **Malicious Software / Data Exfiltration**  
  - Likelihood: 3 (High)  
  - Severity: 3 (High)  
  - Risk Score: 9  

- **Network / Infrastructure Outage**  
  - Likelihood: 2 (Moderate)  
  - Severity: 2 (Moderate)  
  - Risk Score: 4  

**Key Findings:**  
- Public accessibility significantly increased the attack surface  
- Data exfiltration presents the highest organizational risk (Risk Score: 9)  
- Exposure threatens confidentiality of business data and operational continuity  
- Lack of access controls increases likelihood of exploitation  

**Remediation Recommendations:**  
- Implement authentication, authorization, and auditing mechanisms  
- Enforce strong password policies and multi-factor authentication (MFA)  
- Apply role-based access controls (RBAC) and least privilege principles  
- Replace SSL with modern TLS encryption for secure data transmission  
- Implement IP allow-listing to restrict external access  
- Establish regular backups and redundancy for business continuity  

**Security Concepts Applied:**  
- Vulnerability Assessment  
- Risk Management (NIST SP 800-30)  
- CIA Triad (Confidentiality, Integrity, Availability)  
- Access Control & Least Privilege  
- Defense in Depth  
- Business Continuity Planning  

**Supporting Documents:**  
- [Vulnerability Assessment Report (PDF)](Vulnerability-Assessment-Report.pdf)

---

### Incident Handler’s Journal – Multi-Scenario Incident Analysis

**Scenario Summary:**  
In a simulated SOC and enterprise environment, I maintained an incident handler’s journal documenting multiple cybersecurity incidents. Each entry followed structured incident response documentation practices, including identifying the 5 W’s (Who, What, When, Where, Why), analyzing impact, and outlining response actions.

**My Role / Skills Demonstrated:**  
- Documented incidents using structured incident response methodology  
- Applied detection and analysis techniques across multiple attack scenarios  
- Identified root causes and attack vectors  
- Used investigative tools such as VirusTotal and Wireshark  
- Analyzed ransomware, phishing, forced browsing, and network traffic incidents  
- Practiced structured communication for incident reporting  

**Key Incident Scenarios Documented:**  
- **Ransomware attack** at a healthcare clinic initiated via phishing email  
- **Phishing attack investigation** using VirusTotal (51/71 vendor detections, community score -284)  
- **Ransomware and data exfiltration incident** involving forced browsing vulnerability in an e-commerce application  
- **Packet capture analysis** using Wireshark to investigate network activity  

**Tools Used:**  
- VirusTotal (hash and malware analysis)  
- Wireshark (packet capture analysis)  
- Log and alert review techniques  
- Structured 5 W’s incident documentation  

**Security Concepts Applied:**  
- Incident Response Lifecycle (Detection, Analysis, Containment, Eradication, Recovery)  
- Root Cause Analysis  
- Malware Investigation  
- Web Application Vulnerabilities (Forced Browsing)  
- Ransomware Response  
- Network Traffic Analysis  

**Supporting Documents:**  
- [Incident Handler's Journal (PDF)](Incident-Handler's-Journal.pdf)

  ---

### Python Automation – Update Allow List File Using an Algorithm

**Scenario Summary:**  
In a simulated healthcare security environment, I developed a Python algorithm to maintain an IP address allow list for a restricted subnetwork used to access personal patient records. The task required comparing an `allow_list.txt` file against a `remove_list` and automatically removing unauthorized IP addresses from the allow list file.

**My Role / Skills Demonstrated:**  
- Automated access control maintenance using Python  
- Opened and parsed file contents using `with open()` and file objects  
- Converted data between string and list formats for processing (`.read()`, `.split()`, `.join()`)  
- Used iteration and conditional logic to remove unauthorized entries  
- Updated and rewrote files safely using write mode (`"w"`)  

**Key Technical Actions Performed:**  
- Opened `allow_list.txt` in read mode and stored contents in a variable (`ip_addresses`)  
- Converted the allow list from a string into a list using `.split()`  
- Iterated through the allow list and removed any IP addresses found in `remove_list`  
- Converted the updated list back into newline-separated string format using `.join("\n")`  
- Wrote the revised allow list back to `allow_list.txt` using `.write()`  

**Python Concepts Used:**  
- `with open(filename, "r")` and `with open(filename, "w")`  
- File methods: `.read()`, `.write()`  
- String/list methods: `.split()`, `.join()`  
- `for` loops, membership checks (`in`), and conditionals (`if`)  
- List modification with `.remove()`  

**Security Concepts Applied:**  
- Access Control (Allow List Management)  
- Least Privilege (removing unauthorized access)  
- Automation for Security Operations  
- Protection of Sensitive Data (patient records environment)

**Supporting Documents:**  
- [Algorithm for File Updates in Python (PDF)](Algorithm-for-file-updates-in-Python.pdf)
