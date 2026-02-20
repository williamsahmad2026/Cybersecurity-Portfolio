# Cybersecurity Portfolio - Ahmad Jacob Williams

## About Me
I am an entry-level cybersecurity professional with hands-on experience in threat investigation, log analysis, and incident response. Completed the Google Cybersecurity Certificate and lab projects, demonstrating practical skills to help organizations detect, analyze, and mitigate cyber threats. Passionate about protecting systems and continuously developing skills to contribute effectively across security operations.

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
