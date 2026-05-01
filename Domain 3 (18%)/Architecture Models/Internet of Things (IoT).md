## Official Definition
The process of creating a software-based (virtual) representation of something, such as virtual applications, servers, storage, and networks, using a hypervisor.

## Key Characteristics/Technical Details
*   **Hypervisor:** The software that creates and runs virtual machines (VMs).
    *   **Type 1 (Bare Metal):** Runs directly on the hardware (e.g., VMware ESXi, Microsoft Hyper-V).
    *   **Type 2 (Hosted):** Runs on top of an existing OS (e.g., VMware Workstation, Oracle VirtualBox).
*   **VM Escape:** A critical security vulnerability where an attacker breaks out of a VM to access the host OS or other VMs.
*   **VM Sprawl:** The uncontrolled growth of virtual machines, leading to resource exhaustion and security risks (unpatched "forgotten" VMs).
*   **Snapshots:** Point-in-time state of a VM, useful for recovery but not a replacement for backups.
*   **Sandboxing:** Using VMs to isolate suspicious files or applications for testing.

## Real-World Examples
*   **Server Consolidation:** Running multiple web servers, database servers, and mail servers on a single physical host.
*   **Virtual Desktop Infrastructure (VDI):** Hosting user desktops on a central server.
*   **Development/Test Environments:** Quickly spinning up and tearing down identical environments.

## Exam Tips
*   **Keywords:** Hypervisor (Type 1 vs Type 2), VM Escape, VM Sprawl, Snapshots, Elasticity.
*   **Scenario:** If asked about isolating a piece of malware for analysis, "Sandboxing" or "Virtualization" is the answer.
*   **Security Concern:** VM sprawl leads to unmanaged attack surfaces.

## Relationship to other concepts
*   **Availability:** Snapshots and live migration (vMotion) enhance system availability.
*   **Resource Management:** Essential for Cloud computing (IaaS is built on virtualization).
*   **Hardening:** Both the host OS and each guest VM must be independently hardened.