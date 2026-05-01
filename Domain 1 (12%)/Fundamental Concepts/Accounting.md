## Official Definition
*   **Accounting:** The process of tracking user activity and resource consumption. It involves logging actions to provide a trail for auditing and forensics. It is the "What did you do?" phase of the AAA framework.

## Key Mechanisms/Tools
*   **Log Files:** Event logs, syslogs, and application logs that record timestamps, user IDs, and actions taken.
*   **Auditing:** Periodic reviews of logs to detect anomalies or policy violations.
*   **SIEM (Security Information and Event Management):** Centralized systems (e.g., Splunk, Sentinel) that aggregate and analyze logs from multiple sources.
*   **Usage Billing:** Tracking resource use (CPU, storage, bandwidth) for cost allocation.

## Real-World Examples
*   Reviewing **Windows Event Viewer** to see who logged into a server at 2 AM.
*   Using **AWS CloudTrail** to track every API call made in a cloud environment.
*   An ISP tracking data usage to bill a customer for going over their monthly limit.

## Exam Tips
*   **Keyword:** "Logging," "Auditing," "Tracking," "Forensics," "Accountability."
*   **Scenario:** After a security breach, the admin checks the logs to see how the attacker entered. This is an application of Accounting.
*   **CIA vs. AAA:** Accounting is the third "A" in AAA. It is essential for **Non-repudiation**.

## Relationship to other concepts
*   **Non-repudiation:** Accounting provides the evidence (logs) needed to prove a specific user performed a specific action.
*   **Availability:** Excessive logging can sometimes impact system performance or fill up disk space, potentially affecting availability.
