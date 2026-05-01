## Official Definition
An approach to network security that attempts to unify endpoint security technology, user or system authentication, and network security enforcement.

## Key Mechanisms/Tools
*   **Posture Assessment (Health Check):** Checking a device for specific requirements (AV up to date, firewall on, latest patches) before allowing it on the network.
*   **Agents vs. Agentless:**
    *   **Agent-based:** Software installed on the device (persistent or dissolvable).
    *   **Agentless:** Uses network scanning or existing protocols (like SNMP/WMI) to check health.
*   **Quarantine Network:** A restricted VLAN where "non-compliant" devices are sent until they are remediated.
*   **802.1X:** The standard protocol used for port-based NAC (wired or wireless).
*   **Captive Portals:** Used for guest access NAC.

## Real-World Examples
*   A consultant plugs their personal laptop into an office Ethernet jack. The NAC system detects the device, identifies it as "Unknown/Non-compliant," and places it in a Guest VLAN with only internet access.
*   An employee's laptop hasn't updated its antivirus in 3 months; NAC blocks access to the corporate server and redirects the user to a "Remediation Page."

## Exam Tips
*   **Keywords:** Posture assessment, 802.1X, Quarantine, Agent vs. Agentless, Remediation.
*   **Scenario:** Ensuring only "healthy" devices can connect? **NAC**.
*   **Scenario:** If a device fails the health check, it goes to the **Quarantine VLAN**.

## Relationship to other concepts
*   **Wireless Security:** NAC is heavily used in WPA2/WPA3-Enterprise environments via 802.1X.
*   **Asset Management:** NAC helps maintain an accurate inventory of what is on the network.
*   **Zero Trust:** NAC is a fundamental building block of a Zero Trust architecture.
