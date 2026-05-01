## Official Definition
* **OS-based Vulnerability:** A security flaw within the operating system itself (Windows, Linux, macOS) that can be exploited to gain elevated privileges, execute code, or crash the system.

## Key Characteristics/Technical Details
* **Privilege Escalation:** An attacker with limited access exploits an OS flaw to gain administrative (Root/SYSTEM) privileges.
* **Kernel Vulnerabilities:** Flaws in the core of the OS that can lead to complete system compromise.
* **Registry Vulnerabilities (Windows):** Exploiting the Windows Registry to achieve persistence or modify system behavior.
* **Insecure Services:** Default OS services that are unnecessary and provide an entry point for attackers (e.g., Telnet, old SMB versions).
* **Missing Patches:** The most common OS vulnerability; failing to apply security updates from the vendor.

## Real-World Examples
* **BlueKeep (2019):** A critical remote code execution vulnerability in Windows Remote Desktop Services (RDS).
* **Dirty COW (2016):** A privilege escalation vulnerability in the Linux kernel that allowed a local user to gain root access.
* **EternalBlue (2017):** Exploited an OS-level vulnerability in the Windows SMBv1 protocol to spread ransomware.

## Exam Tips
* **Keywords:** Privilege escalation, Kernel, Patching, Registry, Services, SMB, RDP.
* **Scenario:** An attacker "elevates their permissions" or "exploits a flaw in the Windows kernel" to take control of a system.

## Relationship to other concepts
* **Malicious Activity:** Targeted by Network and Application attacks.
* **Mitigation:** Patch management, OS hardening, and using the Principle of Least Privilege.
