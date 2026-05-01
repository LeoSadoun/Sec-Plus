## Official Definition
The process of choosing the most appropriate security controls (Administrative, Technical, Physical) based on risk assessment and organizational needs.

## Key Characteristics/Technical Details
*   **Control Categories:**
    *   **Managerial (Administrative):** Policies, procedures, training, risk assessments.
    *   **Operational:** Everyday human-led activities (BCP/DRP, incident response, physical security guards).
    *   **Technical (Logical):** Hardware/software mechanisms (Firewalls, encryption, MFA).
*   **Control Types (by Function):**
    *   **Preventive:** Stops an incident before it happens (Firewall, locks).
    *   **Detective:** Identifies an incident as it happens or after (Log monitoring, IDS).
    *   **Corrective:** Fixes the damage after an incident (Backups, patches).
    *   **Deterrent:** Discourages an action (Warning signs, cameras).
    *   **Compensating:** Alternative control when a primary one isn't feasible (Using a vault because you can't install a better lock on a door).
    *   **Directive:** Mandates a specific behavior (Policies, laws).

## Real-World Examples
*   **Technical Preventive:** An IPS blocking a known exploit.
*   **Managerial Directive:** An Acceptable Use Policy (AUP) signed by employees.
*   **Operational Corrective:** Restoring a server from a backup after a ransomware attack.
*   **Compensating:** Implementing 24/7 human guards because a biometric scanner is too expensive to install.

## Exam Tips
*   **Keywords:** Preventive, Detective, Corrective, Compensating, Technical, Managerial.
*   **Scenario:** Identifying which category a specific control falls into (e.g., "A backup is which type of control?" Answer: Corrective).
*   **Scenario:** If a legacy system can't be patched, what kind of control do you use? Answer: Compensating.

## Relationship to other concepts
*   **Risk Management:** Control selection is the outcome of the risk mitigation strategy.
*   **Defense in Depth:** Achieved by selecting a mix of control categories (e.g., technical + physical + managerial).