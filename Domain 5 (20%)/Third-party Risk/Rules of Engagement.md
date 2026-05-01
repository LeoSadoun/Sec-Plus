## Official Definition
A document that defines the specific constraints, boundaries, and expectations for a security assessment or penetration test.

## Key Concepts/Technical Details
*   **Scope:** What systems/IPs are allowed to be tested (and which are "off-limits").
*   **Timeline:** When the testing will occur (to avoid peak business hours).
*   **Methods:** What types of attacks are allowed (e.g., No DDoS, no social engineering).
*   **Communication:** Who to contact if a system goes down or a critical vulnerability is found.
*   **Authorized vs. Unauthorized:** Clearly defining what constitutes "hacking" vs. "testing."

## Real-World Examples
*   **Penetration Test RoE:** Specifying that the testers may only attempt to exploit the web server, not the internal database.
*   **Bug Bounty Program:** A public document telling researchers which domains they can test for rewards.
*   **Emergency Contact:** Providing the phone number of the Lead Sysadmin in case the testing accidentally crashes a server.

## Exam Tips
*   **Keywords:** "Constraints," "Scope," "Timeline," "Boundaries," "Penetration Test."
*   **Scenario:** Before a third party starts a pen test, both sides sign a **Rules of Engagement** to ensure no damage is done to production systems.
*   **Get it in Writing:** RoE is critical for legal protection for both the tester and the organization.

## Relationship to other concepts
*   **Penetration Testing (Domain 5):** RoE is the most important document before a pen test begins.
*   **Incident Response:** RoE ensures that the internal security team doesn't mistake a pen test for a real attack.
