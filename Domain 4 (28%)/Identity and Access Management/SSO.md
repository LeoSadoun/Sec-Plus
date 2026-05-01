## Official Definition
An authentication scheme that allows a user to log in with a single ID to any of several related, yet independent, software systems.

## Key Mechanisms/Tools
*   **Federation:** Extending SSO across different organizations or domains.
*   **SAML (Security Assertion Markup Language):** XML-based standard for exchanging authentication and authorization data (Common in web-based SSO).
*   **OIDC (OpenID Connect):** Built on top of OAuth 2.0; uses JSON Web Tokens (JWT) for identity (Common in mobile and modern web apps).
*   **OAuth 2.0:** Primarily for *authorization* (granting access to resources) rather than *authentication*.
*   **IDP (Identity Provider):** The system that authenticates the user (e.g., Azure AD, Okta, Ping).
*   **SP (Service Provider):** The application the user wants to access (e.g., Salesforce, Slack).

## Real-World Examples
*   Logging into your corporate laptop and then automatically being logged into your email, HR portal, and CRM without re-entering your password.
*   "Log in with Google" on a third-party website uses OIDC/OAuth for seamless authentication.

## Exam Tips
*   **Keywords:** SAML, OIDC, OAuth, Federation, IDP, SP.
*   **Scenario:** Which protocol uses XML assertions? **SAML**.
*   **Scenario:** SSO across different companies? **Federation**.
*   **Scenario:** SSO reduces "Password Fatigue."

## Relationship to other concepts
*   **MFA:** SSO should always be paired with MFA, as the "Single Sign-On" is a single point of failure.
*   **Provisioning:** SSO often enables JIT (Just-in-Time) provisioning.
*   **Enterprise Security:** SSO centralizes authentication logs, making monitoring and auditing easier.
