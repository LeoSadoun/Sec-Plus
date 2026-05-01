## Official Definition
*   **Zero Trust:** A security framework based on the principle of "Never Trust, Always Verify." It assumes that threats exist both inside and outside the network and requires strict verification for every user and device.

## Key Mechanisms/Tools
*   **Microsegmentation:** Dividing the network into small, isolated zones to limit lateral movement.
*   **Identity and Access Management (IAM):** Continuous authentication and authorization.
*   **Least Privilege:** Ensuring users only have the bare minimum access.
*   **Continuous Monitoring:** Real-time analysis of user behavior and device health.
*   **Policy Enforcement Points (PEP):** Gatekeepers that verify every request before allowing access to a resource.

## Real-World Examples
*   A user logging into a VPN and being required to perform **MFA** for every individual application they open, rather than just once at the start.
*   Implementing **Software-Defined Perimeter (SDP)** where resources are hidden from the public internet and only visible after authentication.
*   A "BeyondCorp" model where employees can work from any location (home, office, cafe) with the same security posture.

## Exam Tips
*   **Keyword:** "Never trust, always verify," "Lateral movement," "Implicit trust," "Microsegmentation."
*   **Scenario:** A company stops trusting users just because they are on the "internal" office network and starts requiring MFA for everything. This is moving to a Zero Trust architecture.
*   **CIA vs. AAA:** Zero Trust is an architectural approach that heavily leverages all components of **AAA** and the **CIA Triad** to minimize risk.

## Relationship to other concepts
*   **vs. Perimeter-Based Security:** Traditional security used a "castle and moat" approach (trusting everyone inside); Zero Trust removes the "inside" trust.
*   **Least Privilege:** Zero Trust is the ultimate implementation of the Principle of Least Privilege.
