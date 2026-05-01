## Official Definition
* **Cryptographic Attack:** An attempt to bypass or break the security of a cryptographic system by finding weaknesses in its algorithms, implementation, or key management.

## Key Characteristics/Technical Details
* **Birthday Attack:** An attack on hashing algorithms that exploits the probability of two different inputs producing the same hash (a collision).
* **Collision Attack:** Finding two different inputs that produce the same hash value.
* **Downgrade Attack:** Forcing a system to use a weaker, older version of a protocol (e.g., forcing TLS 1.3 down to SSL 3.0) to exploit known vulnerabilities.
* **Replay Attack:** Capturing an encrypted message and resending it later.
* **Known Plaintext Attack:** An attacker has access to both the plaintext and the resulting ciphertext, used to reveal the key.
* **Dictionary / Brute Force on Keys:** Trying to guess the encryption key directly.

## Real-World Examples
* **POODLE Attack:** A downgrade attack that forced browsers to use SSL 3.0, allowing attackers to decrypt sensitive information.
* **MD5 Collisions:** It has been proven that MD5 is no longer secure because collisions can be generated quickly, allowing for the creation of forged digital certificates.

## Exam Tips
* **Keywords:** Collision, Birthday attack, Downgrade, Replay, Plaintext, MD5, SHA-1 (vulnerable).
* **Scenario:** If an attacker "forces a weaker protocol" or "finds two files with the same hash," it's a cryptographic attack.

## Relationship to other concepts
* **Fundamental Concepts:** Directly targets Confidentiality and Integrity.
* **Mitigation:** Using strong, modern algorithms (AES, SHA-256) and secure key management.
