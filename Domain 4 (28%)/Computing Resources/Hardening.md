## Official Definition
The process of securing a system by reducing its surface of vulnerability, which is done by removing unnecessary software, services, and users, and updating existing security settings.

## Key Mechanisms/Tools
*   **Disabling Unnecessary Services:** Turning off ports and protocols that are not required for the system's role (e.g., disabling Telnet or FTP on a web server).
*   **Closing Unused Ports:** Using host-based firewalls to block all traffic except what is explicitly needed.
*   **Default Account Management:** Disabling or renaming the "Administrator" and "Guest" accounts and changing default passwords.
*   **Patch Management:** Regularly applying security updates to the OS and applications.
*   **Least Privilege:** Ensuring users and services have only the permissions necessary to perform their functions.

## Real-World Examples
*   Running a script on a new Linux server to remove `rsh`, `rlogin`, and `rexec` services.
*   Configuring a "Bastion Host" with extremely restrictive settings as it is the only entry point into a private network.

## Exam Tips
*   **Keywords:** Attack surface reduction, disabling services, default passwords, least privilege, patching.
*   **Scenario:** A server was compromised via a service that wasn't even being used? The failure was in the "Hardening" phase.
*   **Scenario:** "Reducing the attack surface" is almost always the answer when discussing hardening.

## Relationship to other concepts
*   **Secure Baselines:** Hardening is the *action*; the baseline is the *standard*.
*   **Vulnerability Management:** Vulnerability scans often identify "low-hanging fruit" that hardening is designed to fix.
*   **Network Security:** Hardening applies to both hosts and network devices (switches/routers).
