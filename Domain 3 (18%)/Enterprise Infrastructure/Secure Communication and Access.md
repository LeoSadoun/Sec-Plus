## Official Definition
Technologies and methods used to ensure that data in transit is protected and that only authorized users/systems can access network resources.

## Key Characteristics/Technical Details
*   **VPN (Virtual Private Network):** Secure tunnel over an unsecure network (Internet).
    *   **IPsec:** Operates at Layer 3 (Network). Common for Site-to-Site.
    *   **SSL/TLS:** Operates at Layer 4-7. Common for Remote Access (clientless).
*   **Network Access Control (NAC):** Inspects devices for health/compliance (e.g., updated AV, latest patches) before allowing connection.
*   **Remote Access Protocols:**
    *   **SSH (Secure Shell):** Secure replacement for Telnet (Port 22).
    *   **RDP (Remote Desktop Protocol):** GUI access (Port 3389). Should be used over VPN.
*   **Unsecure Protocols to Avoid:** Telnet (23), FTP (21), HTTP (80), SNMP v1/v2.
*   **Secure Alternatives:** SSH (22), SFTP (22), HTTPS (443), SNMP v3.

## Real-World Examples
*   **NAC:** A guest connects to the company Wi-Fi and is redirected to a portal to check if their antivirus is active before being granted internet access.
*   **IPsec VPN:** Connecting a branch office router to the main headquarters router securely.
*   **Jump Server (Bastion Host):** A hardened server used to access and manage devices in a high-security zone.

## Exam Tips
*   **Keywords:** NAC, IPsec, SSL/TLS VPN, SSH, Jump Server, Port Security.
*   **Scenario:** How to securely manage a server remotely? SSH.
*   **Scenario:** How to ensure only company-managed laptops with current patches can join the network? NAC.
*   **Protocol Ports:** Memorize common ports (22, 443, 3389).

## Relationship to other concepts
*   **Confidentiality:** Encryption in VPNs and SSH protects data from eavesdropping.
*   **Integrity:** Hashing within protocols like IPsec ensures data isn't modified in transit.
*   **Zero Trust:** Secure communication is a pillar of Zero Trust architecture.