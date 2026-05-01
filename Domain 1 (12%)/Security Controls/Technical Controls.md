### Official Definition
Security controls implemented through hardware, software, or firmware to automate protection and enforce security policies within a system or network.

### Key Characteristics
- **Automated:** Operates without human intervention once configured.
- **Consistent:** Applies rules uniformly across the environment.
- **Logical:** Often referred to as "Logical Controls" in some frameworks.
- **Granular:** Can be applied at the packet, bit, or application level.

### Real-World Examples
1. **Firewalls:** Hardware or software that filters network traffic based on predefined rules.
2. **Encryption:** Using cryptographic algorithms to protect data at rest (AES) or in transit (TLS).
3. **Intrusion Detection/Prevention Systems (IDS/IPS):** Monitoring network traffic for malicious activity and blocking it.
4. **Access Control Lists (ACLs):** Rules applied to routers or switches to permit/deny traffic.
5. **Multi-Factor Authentication (MFA):** Technical systems requiring multiple verification forms (e.g., TOTP, Biometrics).

### Exam Tips
- **Keywords:** "Logic," "Hardware," "Software," "Automated," "Algorithm," "System-level."
- **Pitfall:** Don't confuse technical implementation with operational use. A guard using a computer to check IDs is an **Operational Control**, but the ID badge reader system itself is a **Technical Control**.
- **Interaction:** Technical controls like IPS often act as **Corrective** controls by automatically blocking a detected threat.

### Relationship to other controls
- **Preventive:** A Firewall (Technical) prevents unauthorized access.
- **Detective:** An IDS (Technical) detects suspicious activity.
- **Corrective:** Antivirus (Technical) removes or quarantines a virus after detection.
