## Official Definition
A systematic process for identifying the underlying factor that caused a security incident, rather than just treating the symptoms.

## Key Mechanisms/Tools
*   **The 5 Whys:** Repeatedly asking "Why?" to drill down to the fundamental cause of a problem.
*   **Fishbone Diagram (Ishikawa):** A visual tool used to categorize the potential causes of a problem (People, Process, Technology, etc.).
*   **Log Correlation:** Analyzing logs from multiple sources to piece together the "Kill Chain."
*   **Timeline Analysis:** Creating a minute-by-minute account of the attacker's actions to find the point of initial entry.

## Real-World Examples
*   An incident involved a server being infected with malware. RCA reveals that the "Root Cause" wasn't just the malware, but a missing patch that allowed the malware to exploit a known vulnerability.
*   Finding that a data breach occurred because a developer accidentally hardcoded an API key into a public GitHub repository.

## Exam Tips
*   **Keywords:** Underlying cause, 5 Whys, timeline, Fishbone, "Treating the cause, not the symptom."
*   **Scenario:** What is the purpose of RCA? To identify the **fundamental reason** an incident occurred and prevent recurrence.
*   **Scenario:** RCA is a primary part of the **Lessons Learned** phase.

## Relationship to other concepts
*   **Vulnerability Management:** RCA often identifies gaps in the vulnerability management program (e.g., "The scanner missed this host").
*   **Digital Forensics:** Forensics provides the evidence (logs, file artifacts) needed to perform an accurate RCA.
*   **Hardening:** RCA results often lead to new hardening requirements to close the discovered gap.
