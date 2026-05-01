## Official Definition
The various locations and formats where security-relevant information can be found during a security investigation.

## Key Mechanisms/Tools
*   **Network Sources:**
    *   **NetFlow:** Metadata about network connections (Source/Dest IP, Ports, Bytes).
    *   **Full Packet Capture (PCAP):** The actual content of the network traffic (stored in files readable by Wireshark).
*   **Host Sources:**
    *   **Memory Dumps:** A snapshot of a system's RAM.
    *   **Registry:** Configuration data for Windows systems.
    *   **Prefetch/Shimcache:** Artifacts that show which programs have been run.
*   **Cloud Sources:**
    *   **CloudTrail (AWS) / Activity Logs (Azure):** Records of API calls made to the cloud provider.
    *   **Storage Logs:** Access logs for S3 buckets or Azure Blobs.
*   **Threat Intelligence:** External feeds (STIX/TAXII) that provide context about attackers and their TTPs.

## Real-World Examples
*   An investigator uses a memory dump to find the decryption key for a ransomware-infected machine.
*   Reviewing AWS CloudTrail logs to identify which IAM user created an unauthorized "Backdoor" administrator account.

## Exam Tips
*   **Keywords:** NetFlow, PCAP, Memory dump, Registry, CloudTrail, STIX/TAXII.
*   **Scenario:** Need to see exactly what was inside a malicious packet? Use **Full Packet Capture**.
*   **Scenario:** Need to know what a user was doing in the cloud console? Check **Cloud Activity Logs**.

## Relationship to other concepts
*   **Digital Forensics:** Forensics is the practice of extracting evidence from these sources.
*   **Incident Response:** Identifying the right data source is critical for successful "Detection and Analysis."
*   **Threat Hunting:** Threat hunters use these sources to find subtle anomalies that automated tools miss.
