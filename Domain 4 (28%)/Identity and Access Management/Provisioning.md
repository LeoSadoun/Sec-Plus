## Official Definition
The process of creating, managing, and maintaining user accounts and their associated permissions within an organization's systems.

## Key Mechanisms/Tools
*   **Self-Service Provisioning:** Allowing users to request access or reset passwords via a portal.
*   **Role-Based Access Control (RBAC):** Assigning permissions based on a user's job function rather than individual identity.
*   **Just-in-Time (JIT) Provisioning:** Automatically creating an account the first time a user logs in via SSO.
*   **Deprovisioning:** The critical process of removing or disabling accounts when a user leaves the organization or changes roles.
*   **Access Reviews/Attestation:** Periodic audits to ensure users still require the permissions they have.

## Real-World Examples
*   A new HR employee is added to the "HR-Group" in Active Directory, which automatically gives them access to the payroll system and HR file share.
*   Using an IDP (Identity Provider) like Okta to automatically disable a user's access across 50 different SaaS apps the moment their AD account is disabled.

## Exam Tips
*   **Keywords:** RBAC, deprovisioning, onboarding, offboarding, access review, JIT.
*   **Scenario:** Most important step when an employee is terminated? **Deprovisioning** (disabling the account).
*   **Scenario:** Managing access for 10,000 users? Use **Groups** and **RBAC**.

## Relationship to other concepts
*   **SSO:** Provisioning is often handled automatically by the SSO platform.
*   **Asset Management:** User accounts are digital assets that must be tracked throughout their lifecycle.
*   **Privileged Access Tools:** Highly sensitive accounts require more rigorous provisioning and monitoring.
