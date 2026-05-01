## Official Definition
A system design approach and associated implementation that ensures a prearranged level of operational performance, usually uptime, for a higher than normal period.

## Key Characteristics/Technical Details
*   **Redundancy:** Having multiple components (servers, drives, power supplies) that can take over if one fails.
*   **Failover:** The automatic switching to a redundant or standby computer, server, system, or network upon the failure or abnormal termination of the previously active one.
*   **Clustering:** Connecting multiple computers to work together as a single system.
    *   **Active-Active:** All nodes in the cluster handle traffic simultaneously.
    *   **Active-Passive:** One node handles traffic while others wait in standby.
*   **Load Balancing:** Distributing workloads across multiple computing resources to optimize resource use and prevent overload.
*   **RAID (Redundant Array of Independent Disks):**
    *   **RAID 0:** Striping (Performance only, NO redundancy).
    *   **RAID 1:** Mirroring (Redundancy).
    *   **RAID 5:** Striping with Parity (Redundancy + Performance).
    *   **RAID 6:** Striping with Double Parity (Higher Redundancy).
    *   **RAID 10 (1+0):** Striping and Mirroring (High Performance + High Redundancy).

## Real-World Examples
*   **RAID 1:** Two hard drives mirrored so that if one fails, the server keeps running.
*   **Active-Active Cluster:** Two web servers both receiving traffic from a load balancer. If one dies, the other continues to serve all traffic.
*   **NIC Teaming:** Combining two network interface cards into a single logical link for redundancy.

## Exam Tips
*   **Keywords:** Redundancy, Failover, Uptime, "Five Nines" (99.999%), Load Balancing, RAID.
*   **Scenario:** How to ensure a service stays up if a single server fails? Failover or Clustering.
*   **RAID Tip:** RAID 0 is the only one with NO redundancy. RAID 1 is the simplest redundancy.

## Relationship to other concepts
*   **Availability:** High Availability (HA) is the technical implementation of the "A" in the CIA triad.
*   **SLA (Service Level Agreement):** HA levels are often dictated by SLAs (e.g., 99.9% uptime).