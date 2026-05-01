## Official Definition
Technical and environmental factors that must be addressed when designing and maintaining secure network and server infrastructure.

## Key Characteristics/Technical Details
*   **Device Placement:** Strategic location of firewalls, sensors, and proxies.
*   **Security Zones:**
    *   **DMZ (Demilitarized Zone):** Subnet for outward-facing services (Web, Mail, DNS).
    *   **Internal Network:** Protected area for sensitive data and users.
    *   **Extranet:** Private network for partners/vendors.
    *   **Intranet:** Internal-only network for employees.
*   **Load Balancing:** Distributing traffic across multiple servers to ensure availability and performance.
*   **Honeypots/Honeynets:** Decoy systems or networks designed to attract and study attackers.
*   **Port Security:** Limiting access to physical network ports based on MAC addresses.

## Real-World Examples
*   **DMZ:** Placing a public web server in a DMZ so if it's compromised, the attacker is still separated from the internal database by a second firewall.
*   **Load Balancer:** A cluster of web servers behind an F5 or AWS ELB to handle high traffic spikes.
*   **Air-Gap:** A high-security research computer with no physical or wireless connection to any other network.

## Exam Tips
*   **Keywords:** DMZ, Honeypot, Air-gap, Load Balancing, Port Security.
*   **Scenario:** How to safely host a public website? Put it in a DMZ.
*   **Scenario:** How to detect an intruder's techniques without risking production data? Use a Honeypot.

## Relationship to other concepts
*   **Availability:** Load balancing and redundancy are critical for maintaining the "A" in CIA.
*   **Segmentation:** Zones (DMZ, VLANs) are the primary way to implement network segmentation.
*   **Defense in Depth:** Proper placement of multiple security appliances (FW, IPS, WAF) implements layered security.