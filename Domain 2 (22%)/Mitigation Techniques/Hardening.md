## Official Definition
* **Hardening:** The process of securing a system by reducing its surface of vulnerability through the removal of unnecessary software, services, and users, and the tightening of security settings.

## Key Characteristics/Technical Details
* **Disabling Unused Services:** Turning off ports and services that are not required (e.g., Telnet, FTP).
* **Removing Unnecessary Software:** Deleting bloatware and applications that aren't used.
* **Default Password Changes:** Ensuring no system is left with "admin/admin" or similar credentials.
* **Host-Based Firewalls:** Configuring local firewalls to only allow necessary traffic.
* **Patching:** Keeping the OS and all applications up to date.
* **Disabling Auto-run:** Preventing external media from automatically executing code.

## Real-World Examples
* **STIGs (Security Technical Implementation Guides):** Highly detailed hardening guides provided by the US Department of Defense (DoD).
* **Hardened Gentoo / SELinux:** Operating systems or modules specifically designed with high-security hardening in mind.

## Exam Tips
* **Keywords:** Attack surface, Unused services, Default passwords, Least functionality, Bloatware.
* **Scenario:** If the goal is to "reduce the attack surface" or "close unnecessary ports," use hardening.

## Relationship to other concepts
* **Vulnerabilities:** Directly addresses OS-based and Application vulnerabilities.
* **Configuration Enforcement:** Used to automate and maintain hardening settings.
