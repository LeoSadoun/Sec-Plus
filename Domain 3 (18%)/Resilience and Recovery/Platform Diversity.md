## Official Definition
The practice of using different operating systems, hardware vendors, and service providers to prevent a single point of failure (SPOF) or a single exploit from taking down the entire infrastructure.

## Key Characteristics/Technical Details
*   **OS Diversity:** Mixing Windows and Linux servers. If a zero-day exploit hits Windows, the Linux servers remain unaffected.
*   **Vendor Diversity:** Using firewalls from two different manufacturers (e.g., Palo Alto and Fortinet) in a layered design.
*   **Cloud Diversity:** Using a multi-cloud strategy (AWS and Azure).
*   **Control Diversity:** Mixing technical, administrative, and physical controls.

## Real-World Examples
*   **Layered Firewalls:** An external Cisco firewall and an internal Check Point firewall. An attacker would need to know exploits for both to get through.
*   **Diverse Endpoints:** Providing some employees with MacBooks and others with Windows laptops to mitigate the impact of a platform-specific malware outbreak.

## Exam Tips
*   **Keywords:** Single Point of Failure (SPOF), Vendor Diversity, Multi-cloud, Zero-day mitigation.
*   **Scenario:** Why would a company use two different brands of firewalls? Platform/Vendor Diversity to prevent a single vulnerability from being fatal.
*   **Scenario:** How to avoid being tied to a single cloud provider's outage? Cloud Diversity.

## Relationship to other concepts
*   **Defense in Depth:** Platform diversity is a form of layered security.
*   **Resilience:** Directly increases the system's ability to withstand targeted attacks and vendor-specific failures.