## Official Definition
* **File-based Vector:** A threat vector where malicious code is embedded within a file and delivered to a target system. Once the file is opened or executed, the payload is triggered.

## Key Characteristics/Technical Details
* **Malicious Office Documents:** Using macros (VBA) in Word or Excel to download and execute malware.
* **PDF Exploits:** Leveraging vulnerabilities in PDF readers to execute code when a specially crafted PDF is opened.
* **Executable Files (.exe, .bat, .sh):** Directly delivering malicious binaries that a user is tricked into running.
* **Compressed Files (.zip, .7z, .iso):** Hiding malicious files inside archives to bypass simple email scanners.
* **Image Files (Steganography):** Hiding malicious data or code within the pixels of an image file.

## Real-World Examples
* **Emotet:** Frequently spread via malicious Word documents with macros that, once enabled, would download the primary malware payload.
* **Stuxnet:** Spread partly via infected .lnk (shortcut) files on USB drives.

## Exam Tips
* **Keywords:** Macros, Attachments, Executables, PDF, Archives, Steganography.
* **Scenario:** A user downloads a "report.docx" and is prompted to "Enable Content" (macros), leading to a malware infection.

## Relationship to other concepts
* **Malicious Activity:** The primary method for delivering Malware Attacks.
* **Mitigation:** Disabling macros, file type blocking, sandboxing, and EDR.
