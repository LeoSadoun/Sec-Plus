## Official Definition
An isolated environment that allows programs or files to run without affecting the underlying OS or the rest of the network.

## Key Mechanisms/Tools
*   **Virtual Machines (VMs):** Full OS isolation; high resource usage but strong security boundary.
*   **Containers (Docker/Kubernetes):** OS-level virtualization; shares the kernel but isolates application processes.
*   **Air-Gapping:** Physically isolating a system from all other networks (the ultimate "sandbox").
*   **Analysis Lab:** A dedicated, isolated subnet for malware researchers to detonating files.
*   **Browser Sandboxing:** Modern browsers run each tab in its own process to prevent a malicious site from accessing the local system.

## Real-World Examples
*   An email security appliance opens a suspicious attachment in a "virtual sandbox" to see if it exhibits malicious behavior (like encrypting files) before delivering it to the user.
*   A developer uses a Docker container to test a new application version without risking the stability of their host machine.

## Exam Tips
*   **Keywords:** Isolation, detonation, "virtual environment," malware analysis, snapshot/revert.
*   **Scenario:** How to safely test a suspicious file? Detonate it in a sandbox.
*   **Scenario:** Sandboxing is key for **Malware Analysis**.

## Relationship to other concepts
*   **Incident Response:** Sandboxes are used during the "Eradication" and "Recovery" phases to analyze how a threat works.
*   **Vulnerability Management:** Validation of a patch can be done in a sandbox before production rollout.
*   **Computing Resources:** Sandboxing is a form of resource virtualization and isolation.
