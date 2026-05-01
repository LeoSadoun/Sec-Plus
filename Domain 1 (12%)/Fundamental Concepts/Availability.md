## Official Definition
*   **Availability:** The assurance that systems, networks, and data are accessible and usable when requested by authorized users. It focuses on maintaining uptime and minimizing downtime.

## Key Mechanisms/Tools
*   **Redundancy:** Using multiple components (RAID, load balancers, multiple ISPs) to eliminate single points of failure.
*   **Fault Tolerance:** The ability of a system to continue operating even if a component fails (e.g., dual power supplies).
*   **Patching:** Keeping systems updated to prevent crashes caused by software bugs or security vulnerabilities.
*   **Backups:** Ensuring data can be restored after a loss or ransomware attack.
*   **DDoS Mitigation:** Using scrubbing services or firewalls to prevent service exhaustion attacks.

## Real-World Examples
*   Deploying a **Failover Cluster** for a database so that if one server goes down, the second one takes over immediately.
*   Using **UPS (Uninterruptible Power Supply)** and backup generators to maintain data center operations during a power outage.
*   Implementing **RAID 1 or RAID 5** to ensure a server stays online even if a hard drive fails.

## Exam Tips
*   **Keyword:** "Uptime," "Redundancy," "Denial of Service (DoS)," "Single Point of Failure."
*   **Scenario:** If a web server crashes due to high traffic, Availability is lost.
*   **CIA vs. AAA:** Availability is the "A" in the CIA Triad; it is the goal of many infrastructure technologies, whereas AAA's "Accounting" is about tracking what happened during that uptime.

## Relationship to other concepts
*   **Trade-offs:** High confidentiality (e.g., complex encryption and strict access controls) can sometimes negatively impact availability by slowing down performance or locking out users.
*   **Integrity Dependency:** If the integrity of a system's boot configuration is lost (e.g., corrupted by malware), the system may fail to start, resulting in a loss of availability.
