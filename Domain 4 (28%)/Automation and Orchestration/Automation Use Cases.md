## Official Definition
The application of automated technologies to security tasks to improve efficiency, reduce human error, and accelerate response times.

## Key Mechanisms/Tools
*   **SOAR (Security Orchestration, Automation, and Response):** Integrating different security tools to work together in automated workflows.
*   **Playbooks:** Pre-defined automated workflows that handle specific types of alerts (e.g., "Phishing Email Playbook").
*   **Automated Provisioning/Deprovisioning:** Linking HR systems to AD for zero-touch account management.
*   **Vulnerability Remediation:** Automatically deploying patches to non-critical systems upon discovery of a critical vulnerability.
*   **Continuous Integration/Continuous Deployment (CI/CD):** Integrating security checks (SAST/DAST) directly into the software development pipeline.

## Real-World Examples
*   A SIEM detects a high-severity alert from an EDR; the SOAR platform automatically triggers a playbook to isolate the host and disable the user's account.
*   Automatically rotating API keys every 30 days using a secret management service.

## Exam Tips
*   **Keywords:** SOAR, playbooks, efficiency, human error reduction, response time.
*   **Scenario:** How to handle 10,000 low-level alerts a day? Use **Automation** (SOAR).
*   **Scenario:** Automation is used to scale security operations without increasing headcount.

## Relationship to other concepts
*   **Incident Response:** Automation is the key to reducing **MTTR (Mean Time to Respond)**.
*   **Identity and Access Management:** Automation ensures that offboarding happens immediately, reducing the risk of "Orphaned Accounts."
*   **Monitoring Tools:** Automation takes the output of monitoring tools and turns it into action.
