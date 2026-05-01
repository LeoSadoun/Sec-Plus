## Official Definition
**EDR (Endpoint Detection and Response):** Tools that provide continuous monitoring and response to advanced threats on individual endpoints.
**XDR (Extended Detection and Response):** A platform that integrates data from multiple security layers (endpoint, network, cloud, email) to provide cross-domain visibility and response.

## Key Mechanisms/Tools
*   **EDR Features:**
    *   **Behavioral Analysis:** Detecting "living off the land" techniques (e.g., PowerShell running a suspicious script).
    *   **Forensic Recording:** "Rewinding" the tape to see exactly how a breach happened on a host.
    *   **Isolation:** Automatically disconnecting a compromised host from the network.
*   **XDR Features:**
    *   **Correlation:** Linking an alert from a firewall with an alert from an endpoint to identify a complex multi-stage attack.
    *   **Unified Console:** One place to see and respond to threats across the entire enterprise.
*   **Honeypots:** Decoy systems used to lure and analyze attackers (often integrated with XDR for early detection).

## Real-World Examples
*   An EDR tool detects a user's machine running a macro that downloads an executable; it immediately kills the process and alerts the SOC.
*   XDR correlates a "Successful Login from China" (IAM alert) with "Mass File Deletion" (Endpoint alert) to identify a compromised account in real-time.

## Exam Tips
*   **Keywords:** Endpoint vs. Multi-domain, correlation, isolation, behavioral analysis.
*   **Scenario:** Need to investigate what happened on a *single* laptop after a breach? Use **EDR**.
*   **Scenario:** Need a *holistic* view of security across the whole company? Use **XDR**.

## Relationship to other concepts
*   **Incident Response:** EDR/XDR are the primary tools used for "Containment" and "Eradication."
*   **Monitoring Tools:** XDR is often seen as an evolution of SIEM, with more focus on active response.
*   **Vulnerability Management:** EDR can identify systems being targeted via known vulnerabilities.
