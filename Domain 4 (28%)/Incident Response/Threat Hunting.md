## Official Definition
A proactive security exercise where analysts search through networks to detect and isolate advanced threats that have evaded existing security solutions.

## Key Mechanisms/Tools
*   **Hypothesis-driven Hunting:** Starting with a theory (e.g., "An attacker is using DLL Hijacking on our web servers") and searching for evidence.
*   **Indicators of Compromise (IoCs):** Searching for specific artifacts like file hashes, IP addresses, or domain names associated with known threats.
*   **Indicators of Attack (IoAs):** Focusing on the *behavior* of an attacker (e.g., unusual PowerShell usage, lateral movement) rather than specific files.
*   **Threat Intelligence:** Using external feeds to know what new tactics (TTPs) attackers are using.
*   **Analysis of Big Data:** Using a SIEM or Data Lake to find patterns across billions of logs.

## Real-World Examples
*   A threat hunter searches for all instances of "psexec.exe" being used by non-admin accounts across the entire enterprise to find lateral movement.
*   Using threat intelligence about a new Russian APT (Advanced Persistent Threat) to proactively search for their specific registry modification patterns.

## Exam Tips
*   **Keywords:** Proactive, Hypothesis, IoC vs. IoA, TTP (Tactics, Techniques, and Procedures).
*   **Scenario:** What is the difference between a SOC analyst and a Threat Hunter? The analyst reacts to alerts; the hunter **proactively** looks for what hasn't been alerted on yet.
*   **Scenario:** Hunting assumes the attacker is **already inside** the network.

## Relationship to other concepts
*   **EDR and XDR:** These are the primary tools used by threat hunters to search and isolate threats.
*   **Data Sources:** Threat hunting requires massive amounts of high-fidelity log data.
*   **Incident Response:** Successful threat hunting often *starts* an incident response process.
