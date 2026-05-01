## Official Definition
* **Segmentation:** The process of dividing a network into smaller, isolated sections (subnets or VLANs) to improve security and performance.

## Key Characteristics/Technical Details
* **VLANs (Virtual LANs):** Logically separating a physical switch into multiple broadcast domains.
* **Subnetting:** Dividing an IP network into smaller segments.
* **Air Gapping:** Physically isolating a network from all other networks (including the internet).
* **Microsegmentation:** A security technique that creates secure zones in data centers and cloud environments to isolate workloads from one another and secure them individually.
* **East-West vs. North-South Traffic:**
    * **North-South:** Traffic entering or leaving the data center (protected by perimeter firewalls).
    * **East-West:** Traffic moving between servers within the data center (protected by segmentation).

## Real-World Examples
* **PCI DSS Compliance:** Requires that the "Cardholder Data Environment" (CDE) be segmented from the rest of the corporate network.
* **Industrial Control Systems (ICS):** Often use air-gapping or strict segmentation to protect critical infrastructure from internet-based threats.

## Exam Tips
* **Keywords:** VLAN, Subnet, Air gap, Lateral movement, East-West traffic, DMZ.
* **Scenario:** If the goal is to "prevent an attacker from moving laterally" or "isolate the guest Wi-Fi," use segmentation.

## Relationship to other concepts
* **Malicious Activity:** Effectively limits the "Blast Radius" of a Malware or Network attack.
* **Zero Trust:** Segmentation is a core component of a Zero Trust architecture.
