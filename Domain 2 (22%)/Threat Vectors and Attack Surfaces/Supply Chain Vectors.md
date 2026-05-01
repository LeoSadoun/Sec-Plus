## Official Definition
* **Supply Chain Vector:** A threat vector that targets a third-party vendor or service provider to gain access to their customers' systems or data. It exploits the trust relationship between an organization and its suppliers.

## Key Characteristics/Technical Details
* **Upstream Attack:** Compromising a software vendor to inject malicious code into a legitimate product or update.
* **Hardware Interdiction:** Tampering with physical hardware (e.g., servers, networking gear) during the manufacturing or shipping process.
* **Service Provider Compromise:** Attacking a Managed Service Provider (MSP) to gain access to multiple client networks at once.
* **Third-party Libraries:** Exploiting vulnerabilities in open-source libraries (e.g., Log4j) that are widely used in commercial software.

## Real-World Examples
* **SolarWinds (2020):** Attackers injected a backdoor (Sunburst) into the Orion platform's software updates, affecting thousands of organizations.
* **Target Breach (2013):** Attackers gained access to Target's network by first stealing credentials from an HVAC contractor (a third-party vendor).
* **3CX Desktop App Hack (2023):** A supply chain attack where a legitimate VoIP desktop app was trojanized through a compromised upstream library.

## Exam Tips
* **Keywords:** Third-party, Vendor, Software update, Upstream, MSP, Hardware tampering, Trust relationship.
* **Scenario:** If an attack is described as "entering through a partner's network" or "infecting a software update," think Supply Chain.

## Relationship to other concepts
* **Threat Actors:** Often used by Nation-states (APTs) for high-impact, wide-reach operations.
* **Vulnerabilities:** Directly related to Supply Chain Vulnerabilities.
* **Mitigation:** Vendor risk management, software bill of materials (SBOM), and strict access controls for third parties.
