## Official Definition
* **Isolation:** A security technique that separates a process, application, or system from the rest of the network or host to prevent the spread of malware or unauthorized access.

## Key Characteristics/Technical Details
* **Sandboxing:** Running an application in a restricted environment where it cannot access the host system or network.
* **Containerization (Docker/Kubernetes):** Isolating applications and their dependencies into lightweight, portable containers.
* **Air Gapping:** The ultimate form of isolation; no physical or wireless connection to other networks.
* **Virtualization:** Using VMs to isolate different workloads on the same physical hardware.
* **Browser Isolation:** Running web browsers in a remote, disposable container to protect the user's endpoint from web-based threats.

## Real-World Examples
* **Docker Containers:** Used by developers to ensure that an application's vulnerabilities don't compromise the underlying server.
* **Windows Sandbox:** A temporary, isolated desktop environment where you can run untrusted software without fear of lasting impact to your PC.

## Exam Tips
* **Keywords:** Sandbox, Container, Air gap, Isolation, Blast radius, Guest isolation.
* **Scenario:** If an "untrusted file needs to be opened safely" or a "legacy application must be kept away from the main network," use isolation.

## Relationship to other concepts
* **Virtualization Vulnerabilities:** Targets the isolation mechanisms used in virtualization.
* **Malicious Activity:** Prevents Malware from spreading laterally (limiting the "blast radius").
