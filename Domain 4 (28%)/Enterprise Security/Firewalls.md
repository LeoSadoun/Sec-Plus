## Official Definition
A network security device that monitors and filters incoming and outgoing network traffic based on an organization's previously established security policies.

## Key Mechanisms/Tools
*   **Packet Filtering:** Inspects individual packets based on IP address, port, and protocol (Layer 3/4).
*   **Stateful Inspection:** Tracks the state of active connections; only allows packets that are part of a recognized, established connection.
*   **Next-Generation Firewall (NGFW):** Adds Layer 7 (Application) inspection, IDS/IPS integration, and user-based rules.
*   **ACLs (Access Control Lists):** The set of rules (Permit/Deny) that define what traffic is allowed through the firewall.
*   **Implicit Deny:** The default firewall rule: if traffic isn't explicitly permitted, it is denied.
*   **WAF (Web Application Firewall):** Specialized firewall for HTTP/HTTPS traffic, protecting web apps.

## Real-World Examples
*   Setting a firewall rule to allow inbound HTTPS (Port 443) to a web server but block all inbound SSH (Port 22) from the public internet.
*   An NGFW identifying and blocking a user from downloading a `.zip` file from an unauthorized cloud storage site.

## Exam Tips
*   **Keywords:** ACL, Implicit Deny, Stateful, Layer 3/4 vs. Layer 7, WAF.
*   **Scenario:** Which rule is at the very bottom of every secure firewall? **Implicit Deny**.
*   **Scenario:** Protecting a web server from SQL injection? Use a **WAF**.

## Relationship to other concepts
*   **IDS and IPS:** Firewalls often include IPS functionality in modern deployments.
*   **Hardening:** Configuring host-based firewalls (like Windows Firewall or `iptables`) is a key hardening step.
*   **NAC:** Firewalls can work with NAC to segment the network based on device health or user identity.
