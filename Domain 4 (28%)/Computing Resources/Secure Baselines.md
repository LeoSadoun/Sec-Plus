## Official Definition
A set of minimum security settings and configurations (a "snapshot") that must be applied to a system to ensure it meets an organization's security requirements before being deployed.

## Key Mechanisms/Tools
*   **Imaging:** Creating a "Golden Image" or "Master Image" that contains the OS and pre-configured security settings.
*   **Benchmarks:** Utilizing industry-standard guides like **CIS (Center for Internet Security)** or **DISA STIGs (Security Technical Implementation Guides)**.
*   **Group Policy Objects (GPO):** Centralized management in Windows AD to enforce baseline settings across multiple systems.
*   **Configuration Management:** Tools like SCCM, Ansible, or Puppet to ensure systems do not "drift" from the baseline.

## Real-World Examples
*   Deploying a new Windows 11 workstation using an image where the guest account is disabled, complex passwords are required, and BitLocker is enabled by default.
*   Applying the CIS Benchmark for Apache Web Server to a production Linux box to disable unnecessary modules and restrict directory permissions.

## Exam Tips
*   **Keywords:** Minimum security level, CIS Benchmarks, DISA STIGs, image, configuration drift.
*   **Scenario:** If a system's security posture has weakened over time, it is experiencing "configuration drift" and must be reverted to the baseline.
*   **Scenario:** Standardizing security across 500 laptops? Use a golden image/baseline.

## Relationship to other concepts
*   **Hardening:** Baselines are the *outcome* of the hardening process.
*   **Vulnerability Management:** Baselines provide the "known good" state to compare against during vulnerability scans.
*   **Asset Management:** Tracking which systems are on which baseline version is critical for lifecycle management.
