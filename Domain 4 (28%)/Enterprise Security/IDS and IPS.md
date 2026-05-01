## Official Definition
**IDS (Intrusion Detection System):** Monitors network traffic and system activity for malicious patterns and alerts administrators.
**IPS (Intrusion Prevention System):** Monitors traffic and actively takes steps to block or stop the detected threat.

## Key Mechanisms/Tools
*   **Signature-based Detection:** Matches traffic against a database of known attack patterns (fast but can't detect 0-days).
*   **Anomaly-based (Behavioral) Detection:** Establishes a "baseline" of normal activity and alerts on deviations (can detect 0-days but high false positives).
*   **Heuristic Detection:** Uses algorithms/logic to identify suspicious characteristics (e.g., "if X and Y and Z happen, it's probably an attack").
*   **HIDS vs. NIDS:**
    *   **HIDS (Host-based):** Installed on a single system (e.g., OSSEC).
    *   **NIDS (Network-based):** Monitors traffic on the wire (e.g., Snort, Suricata).
*   **In-line vs. Passive:**
    *   **In-line (IPS):** Traffic flows *through* the device; it can block in real-time.
    *   **Passive (IDS):** Receives a copy of the traffic (SPAN/TAP); can only alert.

## Real-World Examples
*   A NIDS detects a pattern of "SYN Scanning" against the network and alerts the SOC.
*   An IPS automatically drops packets containing a known Buffer Overflow exploit targeting a legacy server.

## Exam Tips
*   **Keywords:** Signature vs. Anomaly, HIDS vs. NIDS, False Positive, Out-of-band (Passive) vs. In-band (In-line).
*   **Scenario:** Which system can *stop* an attack as it happens? **IPS**.
*   **Scenario:** High false positives are common with **Anomaly-based** detection.

## Relationship to other concepts
*   **Firewalls:** NGFWs integrate IPS functionality directly into the firewall.
*   **Monitoring Tools:** IDS alerts are a primary feed into a SIEM.
*   **Incident Response:** IDS/IPS are critical for the "Detection" phase of IR.
