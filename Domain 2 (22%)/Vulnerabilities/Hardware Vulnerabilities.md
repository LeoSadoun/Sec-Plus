## Official Definition
* **Hardware Vulnerability:** A weakness in a physical computer component or its firmware that can be exploited to compromise the security of the system. These are often difficult to patch and may require physical replacement.

## Key Characteristics/Technical Details
* **Firmware Flaws:** Vulnerabilities in the BIOS/UEFI or device-specific firmware (e.g., in a network card or SSD).
* **Side-Channel Attacks:** Exploiting information leaked from the physical implementation of a system (e.g., power consumption, electromagnetic leaks, timing information).
* **Rowhammer:** A physical vulnerability in DRAM where rapidly accessing a row of memory can cause "bit flipping" in adjacent rows.
* **Hardware Backdoors:** Malicious circuits or "logic bombs" intentionally added to hardware during design or manufacturing.
* **Supply Chain Interdiction:** Physical tampering with hardware while it is in transit to the customer.

## Real-World Examples
* **Spectre and Meltdown (2018):** Critical vulnerabilities in modern microprocessors (Intel, AMD, ARM) that exploit "speculative execution" to leak sensitive data from memory.
* **Bloomberg "The Big Hack" (Alleged):** A controversial report claiming that Chinese spies planted tiny malicious chips on motherboards used by major US companies (though widely disputed).

## Exam Tips
* **Keywords:** Firmware, Side-channel, Specter/Meltdown, Bit-flipping, Physical tampering, TPM.
* **Scenario:** If an attack is "independent of the OS" or "exploits CPU design," it's a hardware vulnerability.

## Relationship to other concepts
* **Threat Vectors:** Often exploited via Supply Chain Vectors.
* **Mitigation:** Hardware Root of Trust (TPM), secure boot, and physical security controls.
