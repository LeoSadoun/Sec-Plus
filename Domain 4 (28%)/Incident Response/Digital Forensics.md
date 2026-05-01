## Official Definition
The application of scientific investigation techniques to digital evidence to identify, preserve, recover, and analyze data related to a security incident or crime.

## Key Mechanisms/Tools
*   **Order of Volatility:** The sequence in which evidence must be collected, from most fragile to most permanent:
    1.  CPU Cache / Registers
    2.  Routing Table / ARP Cache / RAM
    3.  Temporary File Systems (Swap/Pagefile)
    4.  Disk (HDD/SSD)
    5.  Remote Logging / Monitoring Data
    6.  Physical Configuration / Network Topology
    7.  Archival Media (Backups/Tapes)
*   **Chain of Custody:** Documenting everyone who handled the evidence to ensure it remains admissible in court.
*   **Imaging (Bit-stream copy):** Creating a bit-for-bit copy of a drive; never work on the original evidence.
*   **Hashing (MD5/SHA-256):** Using cryptographic hashes to prove the integrity of the forensic image (it hasn't been modified).
*   **Write Blockers:** Hardware devices that prevent any data from being written to the evidence drive during the imaging process.

## Real-World Examples
*   A forensic analyst uses a write blocker to image a suspect's laptop and then calculates the SHA-256 hash of both the original and the copy to prove they match.
*   Recovering "deleted" files from an SSD using specialized forensic software that bypasses the file system's pointers.

## Exam Tips
*   **Keywords:** Order of Volatility, Chain of Custody, Hashing, Write Blocker, Imaging.
*   **Scenario:** What is the first thing you should collect? **RAM** (it's the most volatile).
*   **Scenario:** Why do you hash a forensic image? To ensure **Integrity** and **Admissibility**.

## Relationship to other concepts
*   **Incident Response:** Forensics provides the "Ground Truth" during an incident investigation.
*   **Legal/Compliance:** Forensics is critical for law enforcement involvement or meeting regulatory reporting requirements.
*   **Data Sources:** Forensics analysts work with disk images, memory dumps, and log data.
