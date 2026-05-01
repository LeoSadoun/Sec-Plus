## Official Definition
The continuous process of checking systems and processes to ensure they remain in compliance with security requirements.

## Key Concepts/Technical Details
*   **Continuous Monitoring:** Moving away from "point-in-time" audits to real-time compliance tracking.
*   **Automated Tools:** Using SIEM, GRC (Governance, Risk, and Compliance) tools, and configuration management to detect drifts.
*   **Configuration Drift:** When a system’s settings change over time, moving away from the "Secure Baseline."
*   **Sampling:** Periodically checking a subset of systems to verify compliance (if continuous monitoring is not possible).

## Real-World Examples
*   **SIEM Alerts:** An alert triggers when a user is granted "Domain Admin" privileges, violating the policy of Least Privilege.
*   **File Integrity Monitoring (FIM):** Detecting unauthorized changes to critical system files.
*   **Vulnerability Scanning:** Scanning weekly to ensure no new "Critical" vulnerabilities have appeared.

## Exam Tips
*   **Keywords:** "Continuous," "Real-time," "Automated," "Drift," "Verification."
*   **Scenario:** A tool that alerts administrators whenever a firewall rule is changed is a form of **Compliance Monitoring**.
*   **Baseline:** Monitoring is only effective if you have a known-good baseline to compare against.

## Relationship to other concepts
*   **Operations (Domain 4):** Monitoring is a core operational activity that supports compliance.
*   **Incident Response:** Compliance monitoring often detects the early signs of a security breach.
