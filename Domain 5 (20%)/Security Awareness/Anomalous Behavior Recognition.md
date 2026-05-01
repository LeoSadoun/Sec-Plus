## Official Definition
Training users to identify patterns or actions that deviate from the "normal" baseline, which may indicate a security incident or insider threat.

## Key Concepts/Technical Details
*   **Baseline:** Understanding what "normal" looks like (e.g., standard login times, typical data transfer volumes).
*   **UEBA (User and Entity Behavior Analytics):** Technical tools that assist humans in identifying these anomalies.
*   **Indicators of Compromise (IoC):** Technical artifacts (IPs, hashes) that signal a breach.
*   **Indicators of Attack (IoA):** Behavioral patterns (lateral movement, unusual PowerShell use) that signal an attack is in progress.
*   **Insider Threat Signs:** Employees accessing data they don't need, working unusual hours, or attempting to bypass controls.

## Real-World Examples
*   **Impossible Travel:** Detecting a login from New York and then 10 minutes later from London.
*   **Data Exfiltration:** A user who normally downloads 10MB/day suddenly downloading 5GB.
*   **Physical Security:** Reporting a "tailgater" who follows an employee into a secure area without badging in.

## Exam Tips
*   **Keywords:** "Deviation," "Baseline," "Normal," "Anomaly," "Insider Threat," "UEBA."
*   **Scenario:** An employee noticed a colleague trying to use a USB drive on a restricted workstation and reported it. This is **Anomalous Behavior Recognition**.
*   **Education:** Teaching users that "If you see something, say something" applies to digital behavior too.

## Relationship to other concepts
*   **Monitoring (Domain 4):** User recognition supplements technical monitoring tools.
*   **Incident Response:** Early recognition of anomalies can significantly reduce the "dwell time" of an attacker.
