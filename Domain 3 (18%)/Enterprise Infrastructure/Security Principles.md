## Official Definition
Foundational concepts and strategies used to design, implement, and maintain a secure enterprise environment.

## Key Characteristics/Technical Details
*   **Least Privilege:** Users/systems should only have the minimum access necessary to perform their function.
*   **Defense in Depth (Layered Security):** Using multiple security controls at different levels (Physical, Network, Host, Application, Data).
*   **Separation of Duties:** Dividing sensitive tasks among multiple people to prevent fraud or error.
*   **Keep It Simple (KISS):** Avoiding unnecessary complexity in security designs, as complexity often leads to vulnerabilities.
*   **Zero Trust:** "Never trust, always verify." Every access request is authenticated, authorized, and encrypted regardless of origin.
*   **Implicit Deny:** The default stance should be to block all traffic/access unless explicitly allowed.

## Real-World Examples
*   **Least Privilege:** A developer having "Read/Write" access to a code repository but no access to the production database.
*   **Defense in Depth:** Using a firewall, an IDS/IPS, host-based antivirus, and file encryption all together.
*   **Separation of Duties:** One person creates a new user account, while a second person approves their access rights.

## Exam Tips
*   **Keywords:** Least Privilege, Layered Security, Separation of Duties, Zero Trust, Implicit Deny.
*   **Scenario:** If a user is granted more access than needed, it violates "Least Privilege."
*   **Scenario:** If a single person can authorize and execute a wire transfer, it violates "Separation of Duties."

## Relationship to other concepts
*   **CIA Triad:** These principles directly support Confidentiality (Least Privilege), Integrity (Separation of Duties), and Availability (Defense in Depth).
*   **Identity and Access Management (IAM):** Core implementation area for Least Privilege and Zero Trust.