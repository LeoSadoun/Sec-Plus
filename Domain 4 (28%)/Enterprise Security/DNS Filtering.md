## Official Definition
A security control that intercepts DNS queries and blocks access to known malicious domains or unauthorized categories of websites.

## Key Mechanisms/Tools
*   **Blocklists/Allowlists:** Databases of domains categorized as "Malware," "Phishing," "Gambling," etc.
*   **DNS Sinkhole:** Redirecting a query for a malicious domain to a safe, controlled IP address (often used for botnet disruption).
*   **DNS over HTTPS (DoH):** Encrypting DNS queries to prevent interception or tampering (can sometimes bypass filtering).
*   **Cloud-based Resolvers:** Services like Cisco Umbrella, Cloudflare for Teams, or Quad9.

## Real-World Examples
*   A user clicks a link in a phishing email; the DNS filter identifies the domain as "Malicious" and displays a block page instead of resolving the IP.
*   An organization blocks the "Social Media" category during work hours to increase productivity and reduce the attack surface.

## Exam Tips
*   **Keywords:** Blocklist, Sinkhole, Category-based filtering, Phishing prevention.
*   **Scenario:** How to prevent users from visiting known malware sites without inspecting all traffic? **DNS Filtering**.
*   **Scenario:** Redirecting botnet traffic to a fake server? **DNS Sinkhole**.

## Relationship to other concepts
*   **DLP:** DNS filtering can block access to unauthorized file-sharing sites.
*   **Identity and Access Management:** Modern DNS filters can apply different rules based on the user's AD group.
*   **Incident Response:** Reviewing DNS logs is a key part of investigating command-and-control (C2) activity.
