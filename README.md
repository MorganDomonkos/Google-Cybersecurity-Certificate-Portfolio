# Google Cybersecurity Professional Certificate Capstone

A collection of labs, projects, and security audits completed during the Google Cybersecurity Professional Certificate program. This repository demonstrates proficiency in Python, SQL, Linux, and SIEM tools.

---

## Skills & Tools

* **Languages:** Python (Automation), SQL (Data querying)
* **Operating Systems:** Linux (CLI), Windows, macOS
* **Security Tools:** Chronicle (SIEM), Suricata (IDS), Wireshark, Tcpdump, VirusTotal
* **Frameworks:** NIST CSF, NIST SP 800-53, NIST SP 800-61, HIPAA, PCI DSS

---

## Featured Projects

### Python: Algorithm for File Updates
* **Scenario:** Developed an automation script to manage server access by removing revoked IP addresses from a restricted "allow list" text file.
* **Implementation:** Utilized Python’s `with` statements for secure file I/O, `.split()` and `.join()` for data conversion, and iterative loops to filter unauthorized identifiers.
* **Tools:** Python (Standard Library)

### Security Operations: Network Traffic Analysis
* **Scenario:** Investigated a DNS flood and DDoS attack that caused a service outage by analyzing malicious packet signatures.
* **Implementation:** Analyzed network telemetry to identify the attack vector, reconstructed the incident timeline, and documented remediation steps.
* **Tools:** Suricata, tcpdump, Wireshark

### Governance, Risk, & Compliance: Controls Audit
* **Scenario:** Performed a compliance audit to align organizational security posture with NIST RMF and regulatory standards.
* **Implementation:** Evaluated technical and administrative controls (e.g., encryption, firewall rules) against HIPAA, PCI DSS, and GDPR requirements.
* **Tools:** NIST SP 800-53, Compliance Checklists

### Incident Response: Handler’s Journal
* **Scenario:** Documented the identification, triage, and analysis of simulated security events to refine organizational response protocols.
* **Implementation:** Performed file hash analysis and categorized threats using industry-standard frameworks to ensure an accurate audit trail.
* **Tools:** VirusTotal, Pyramid of Pain, Incident Handler's Journal

### Data Security: Access Control & Leak Mitigation
* **Scenario:** Enforced the Principle of Least Privilege (PoLP) and investigated potential data exfiltration points.
* **Implementation:** Mapped user roles to permissions using an Access Control Worksheet and recommended Data Loss Prevention (DLP) controls.
* **Tools:** IAM, RBAC, DLP concepts

### Linux: File Permissions via CLI
* **Scenario:** Auditing server files to ensure the Principle of Least Privilege (PoLP).
* **Implementation:**
  * Used `ls -l` to identify over-privileged files.
  * Applied `chmod` to restrict read/write/execute permissions.
  * Used `chown` to reassign file ownership to authorized users.

### SQL: Security Log Investigation
* **Scenario:** Investigated employee data and logs to identify potential unauthorized access.
* **Implementation:**
  * Used `WHERE` and `AND` filters to isolate failed login attempts.
  * Utilized `OR` logic to query specific investigation dates.
  * Applied `NOT
