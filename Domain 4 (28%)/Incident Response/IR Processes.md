## Official Definition
A structured process used by organizations to identify, respond to, and recover from cybersecurity incidents.

## Key Mechanisms/Tools
*   **Incident Response Life Cycle (NIST SP 800-61):**
    1.  **Preparation:** Creating policies, training teams, and deploying tools.
    2.  **Detection and Analysis:** Identifying an incident and determining its scope/impact.
    3.  **Containment, Eradication, and Recovery:**
        *   **Containment:** Stopping the spread (Short-term vs. Long-term).
        *   **Eradication:** Removing the threat (deleting malware, disabling accounts).
        *   **Recovery:** Restoring systems to normal operation.
    4.  **Post-Incident Activity:** "Lessons Learned" to improve the process for next time.
*   **CSIRT (Computer Security Incident Response Team):** The group of people responsible for executing the IR plan.
*   **Communication Plan:** Defining who to notify (internal management, legal, external PR, law enforcement).

## Real-World Examples
*   A company experiences a ransomware attack. The CSIRT follows their "Ransomware Playbook" to isolate infected subnets (Containment), wipe and restore servers from backups (Eradication/Recovery), and then holds a meeting to discuss how the initial entry occurred (Lessons Learned).
*   Using a SIEM to detect an unusual volume of data leaving the network and automatically triggering an IR analysis ticket.

## Exam Tips
*   **Keywords:** Preparation, Detection, Containment, Eradication, Recovery, Lessons Learned.
*   **Scenario:** What is the very first step in the IR lifecycle? **Preparation**.
*   **Scenario:** What do you do *after* an incident is over to prevent it from happening again? **Lessons Learned**.

## Relationship to other concepts
*   **Automation and Orchestration:** SOAR platforms automate the Detection and Containment phases.
*   **Digital Forensics:** Forensics is often a sub-task within the "Analysis" and "Eradication" phases.
*   **Reporting:** Incident reports are a key outcome of the "Post-Incident Activity" phase.
