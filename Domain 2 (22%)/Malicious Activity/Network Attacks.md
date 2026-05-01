## Official Definition
* **Network Attack:** An attack that targets the network infrastructure, protocols, or traffic to disrupt service or steal data.

## Key Characteristics/Technical Details
* **Denial of Service (DoS) / Distributed DoS (DDoS):** Overwhelming a target with traffic to make it unavailable.
* **Man-in-the-Middle (MitM):** Intercepting traffic between two hosts.
* **ARP Poisoning:** Sending fake ARP messages to link an attacker's MAC address with a legitimate IP address.
* **DNS Spoofing / Poisoning:** Redirecting users to a malicious website by corrupting DNS records.
* **MAC Spoofing:** Changing a device's MAC address to bypass access control lists (ACLs).
* **IP Spoofing:** Creating IP packets with a forged source IP address to hide identity or impersonate a host.
* **VLAN Hopping:** An attack where an attacker on one VLAN gains access to traffic on another VLAN.

## Real-World Examples
* **Mirai Botnet (2016):** A massive DDoS attack that targeted Dyn (a major DNS provider), taking down large parts of the internet.
* **GitHub DDoS (2018):** One of the largest recorded DDoS attacks, reaching 1.35 Tbps using memcached amplification.

## Exam Tips
* **Keywords:** DDoS, MitM, ARP poisoning, DNS poisoning, Spoofing, VLAN hopping.
* **Scenario:** If traffic is "redirected to the wrong site" or a "server is overwhelmed by requests," it's a network attack.

## Relationship to other concepts
* **Threat Vectors:** Uses Unsecure Networks.
* **Mitigation:** Firewalls, IDS/IPS, and network segmentation.
