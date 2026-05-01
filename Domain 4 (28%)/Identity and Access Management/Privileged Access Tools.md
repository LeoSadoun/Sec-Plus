## Official Definition
Tools and processes used to manage, monitor, and secure accounts that have elevated permissions (e.g., Domain Admins, Root, Service Accounts).

## Key Mechanisms/Tools
*   **PAM (Privileged Access Management):** Platforms like CyberArk or BeyondTrust that "vault" administrative passwords.
*   **Password Vaulting:** Storing highly sensitive passwords in an encrypted database; users "check out" the password when needed.
*   **Session Recording:** Capturing a video or text log of everything a privileged user does during their session.
*   **Dual Control:** Requiring two people to approve an action (e.g., checking out a Root password).
*   **Credential Rotation:** Automatically changing administrative passwords every few hours or after every use.
*   **Privilege Elevation:** Using tools like `sudo` or "User Account Control" (UAC) to temporarily gain higher rights.

## Real-World Examples
*   A systems administrator needs to change a firewall rule; they log into the PAM vault, check out the credentials, and their session is recorded for audit purposes.
*   Automatically rotating the "Service Account" password for a database every 24 hours without human intervention.

## Exam Tips
*   **Keywords:** PAM, vault, rotation, session recording, dual control, least privilege.
*   **Scenario:** How to prevent a "rogue admin" from causing damage? **Session Recording** and **Dual Control**.
*   **Scenario:** "Checking out" a credential for a limited time is a key PAM feature.

## Relationship to other concepts
*   **Hardening:** Disabling shared administrative accounts and using individual privileged accounts is a core hardening step.
*   **Compliance:** Many regulations (SOX, PCI) require strict monitoring of privileged access.
*   **Incident Response:** PAM logs are invaluable for investigating internal breaches or accidental system changes.
