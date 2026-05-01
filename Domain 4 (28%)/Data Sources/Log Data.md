## Official Definition
A record of events that occur within an organization's systems and networks, serving as the primary evidence for security monitoring and investigation.

## Key Mechanisms/Tools
*   **Syslog:** The standard protocol for message logging on Linux/Unix systems and network devices.
*   **Windows Event Logs:** Categorized into Application, Security, Setup, System, and Forwarded Events.
*   **Log Levels:** Defining the severity of the log entry (e.g., Debug, Info, Warning, Error, Critical/Emergency).
*   **Log Management:** The process of collecting, aggregating, storing, and rotating logs to manage disk space.
*   **Log Forwarding/Ingestion:** Sending logs from individual hosts to a central SIEM using agents or protocols like syslog-ng or Winlogbeat.

## Real-World Examples
*   A Windows Security Log entry with Event ID 4625 (An account failed to log on) is used to detect brute force attempts.
*   A firewall log showing a high volume of outbound traffic on Port 53 (DNS) to an unknown IP, suggesting DNS tunneling for data exfiltration.

## Exam Tips
*   **Keywords:** Syslog, Event ID, Log rotation, aggregation, ingestion.
*   **Scenario:** Which log should you check to find out who accessed a specific file? **Security Log** (with object access auditing enabled).
*   **Scenario:** Centralizing logs from 1,000 servers? Use a **SIEM**.

## Relationship to other concepts
*   **Alerting and Monitoring:** Monitoring tools analyze log data to trigger alerts.
*   **Incident Response:** Logs are the foundation of "Detection" and "Analysis" in the IR lifecycle.
*   **Digital Forensics:** Log data is a less volatile but highly valuable source of evidence.
