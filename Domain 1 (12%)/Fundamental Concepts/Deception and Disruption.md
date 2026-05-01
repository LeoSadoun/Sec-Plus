## Official Definition
*   **Deception and Disruption:** Proactive security techniques used to mislead, confuse, and delay attackers. The goal is to divert them away from real assets and toward fake ones to gain intelligence on their methods.

## Key Mechanisms/Tools
*   **Honeypots:** A decoy system designed to be probed, attacked, or compromised.
*   **Honeyfiles:** Decoy files (e.g., "passwords.txt") that trigger an alert when accessed.
*   **Honeynets:** An entire network of decoys.
*   **Honeytokens:** Pieces of data (like a fake API key) that are tracked to see who uses them.
*   **DNS Sinkholes:** Redirecting malicious traffic to a controlled server to prevent communication with a C2 (Command and Control) server.

## Real-World Examples
*   Setting up a **fake database server** with vulnerable settings to see what kind of SQL injection attacks are being used in the wild.
*   Placing a file named **"Salary_Data.xlsx"** on a public share; the file contains no real data but notifies the security team whenever it is opened.
*   Using a **DNS Sinkhole** to redirect botnet traffic away from its controller and toward a security researcher's server.

## Exam Tips
*   **Keyword:** "Decoy," "Divert," "Mislead," "Honeypot," "Sinkhole."
*   **Scenario:** A security team wants to learn an attacker's "TTPs" (Tactics, Techniques, and Procedures) without risking real data. They should deploy a Honeypot.
*   **CIA vs. AAA:** These techniques primarily support **Integrity** and **Availability** by protecting real assets, while also providing **Accounting** data about the attacker.

## Relationship to other concepts
*   **Intrusion Detection:** Deception tools act as high-fidelity sensors; any activity on a honeypot is almost certainly malicious.
*   **Incident Response:** Data gathered from deception tools is used to improve future defenses and response strategies.
